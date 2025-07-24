# Combined Rules from awesome-cursorrules

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\angular\angular-general.mdc

- Adhere to the official Angular Style Guide.
- Use `OnPush` change detection for performance.
- Keep components small and focused on a single responsibility.
- Use lazy loading for feature modules.
- Provide specific types instead of `any`.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\angular\angular-template-hints.mdc

- Use the `async` pipe for observables.
- Use `trackBy` for `*ngFor` loops.
- Avoid complex logic in templates.
- Use `ng-container` to avoid unnecessary elements.
- Use ARIA attributes for accessibility.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\angular\general-reasoning.mdc

- Explain the 'why' behind a solution.
- Consider trade-offs of different approaches.
- Link to official documentation or authoritative sources.
- Provide code examples to illustrate points.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\angular\refactoring-existing-code.mdc

- Identify code smells (e.g., large components, duplicate code).
- Break down large components into smaller, reusable ones.
- Replace manual subscription management with `takeUntil` or `async` pipe.
- Ensure changes are covered by tests.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\angular\typescript-coding-style.mdc

- Use `const` by default; use `let` only when a variable needs to be reassigned.
- Use early returns (guard clauses) to avoid nested `if` statements.
- Prefer interfaces over classes for data models.
- Use arrow functions for callbacks and short anonymous functions.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\astro\astro-development-guidelines.mdc

- Embrace Astro's component-based architecture.
- Use Astro islands for interactive components.
- Leverage Astro's content collections for Markdown and MDX.
- Optimize for performance with partial hydration.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\astro\commit-message-guidelines.mdc

- Follow the Conventional Commits specification.
- Start with a type (e.g., `feat`, `fix`, `docs`).
- Write a concise and descriptive subject line.
- Provide more context in the commit body if necessary.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\astro\custom-slash-commands.mdc

- Define clear and intuitive command names.
- Document the purpose and usage of each command.
- Handle potential errors and provide helpful feedback.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\astro\general-coding-style.mdc

- Write clean, readable, and maintainable code.
- Use consistent formatting (e.g., Prettier).
- Add comments to explain complex or non-obvious code.
- Follow the DRY (Don't Repeat Yourself) principle.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\astro\tailwindcss-styling-guidelines.mdc

- Use Tailwind's utility-first approach for styling.
- Configure `tailwind.config.js` to customize the design system.
- Use `@apply` for custom, reusable component classes sparingly.
- Leverage Tailwind's responsive design features.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\javascript\general-javascript-rules.mdc

- Use modern JavaScript (ES6+).
- Avoid global variables.
- Use strict mode (`'use strict';`).
- Handle asynchronous operations with Promises or `async/await`.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\javascript\javascript-code-quality.mdc

- Write JSDoc comments for functions and modules.
- Use a linter (e.g., ESLint) to enforce code quality.
- Write unit tests for critical logic.
- Keep functions short and focused.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\nextjs\best-practices-for-nextjs-app-router.mdc

- Use Server Components by default.
- Co-locate pages, layouts, and components.
- Use Route Handlers for API endpoints.
- Leverage nested layouts for shared UI.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\nextjs\html-tailwindcss-and-javascript-best-practices.mdc

- Write semantic HTML5.
- Use Tailwind CSS for responsive and utility-first styling.
- Follow JavaScript best practices for clean and maintainable code.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\nextjs\nextjs-14-error-handling-and-metadata.mdc

- Use `error.js` files for handling errors in nested routes.
- Use `global-error.js` for root-level error handling.
- Use the Metadata API for SEO optimization.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\nodejs\es-module-nodejs-guidelines.mdc

- Use the `.mjs` extension or set `"type": "module"` in `package.json`.
- Use `import` and `export` statements.
- Understand differences in `__dirname` and `__filename`.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\react\react-typescript-naming-convention-rules.mdc

- Use PascalCase for component names (e.g., `MyComponent`).
- Use camelCase for props and state variables (e.g., `userName`).
- Prefix interfaces with `I` (e.g., `IUserProps`).

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\react\react-typescript-rules.mdc

- Use TypeScript with React for type safety.
- Define props and state with interfaces.
- Use functional components with hooks.
- Avoid `any` type.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\react\react-ui-styling-with-tailwind-and-shadcn-ui.mdc

- Use Tailwind CSS for utility-first styling.
- Use Shadcn UI for accessible and customizable components.
- Configure `tailwind.config.js` to match the design system.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\nextjs-react-tailwind-cursorrules-prompt-file\.cursorrules

- You are an expert in TypeScript, Node.js, Next.js App Router, React, Shadcn UI, and Tailwind and Framer Motion.
- Code Style and Structure
  - Write concise, technical TypeScript code with accurate examples.
  - Use functional and declarative programming patterns; avoid classes.
  - Prefer iteration and modularization over code duplication.
  - Use descriptive variable names with auxiliary verbs (e.g., isLoading, hasError).
  - Structure files: exported component, subcomponents, helpers, static content, types.
- Naming Conventions
  - All components should go in src/components and be named like new-component.tsx
  - Use lowercase with dashes for directories (e.g., components/auth-wizard).
  - Favor named exports for components.
- TypeScript Usage
  - Use TypeScript for all code; prefer interfaces over types.
  - Avoid enums; use maps instead.
  - Use functional components with TypeScript interfaces.
- Syntax and Formatting
  - Use the "function" keyword for pure functions.
  - Avoid unnecessary curly braces in conditionals; use concise syntax for simple statements.
  - Use declarative JSX.
- UI and Styling
  - Use Shadcn UI, and Tailwind for components and styling.
  - Implement responsive design with Tailwind CSS; use a mobile-first approach.
- Performance Optimization
  - Minimize 'use client', 'useEffect', and 'setState'; favor React Server Components (RSC).
  - Wrap client components in Suspense with fallback.
  - Use dynamic loading for non-critical components.
  - Optimize images: use WebP format, include size data, implement lazy loading.
- Key Conventions
  - Use 'nuqs' for URL search parameter state management.
  - Optimize Web Vitals (LCP, CLS, FID).
  - Limit 'use client':
    - Favor server components and Next.js SSR.
    - Use only for Web API access in small components.
    - Avoid for data fetching or state management.
  - Follow Next.js docs for Data Fetching, Rendering, and Routing.
  - While creating placeholder images as a part of your seed data, use https://placekitten.com/
  - Place both the /app and /components folders under a /src directory. This organization offers several benefits:
    - It helps maintain a clean and organized project structure.
    - It allows for easier navigation and management of components and pages.
    - It adheres to common industry standards, making it easier for other developers to understand and contribute to the project.
    - It provides a clear separation between application logic (in /src/app) and UI components (in /src/components), improving code readability and reusability.
    - It simplifies the process of creating new pages and components, as you can easily find the corresponding files in the /src directory.
    - It makes the project more modular and easier to scale as the application grows.
    - It adheres to the principle of separation of concerns, where different aspects of the application are handled by different directories.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\nextjs-react-typescript-cursorrules-prompt-file\.cursorrules

You are an expert in Solidity, TypeScript, Node.js, Next.js 14 App Router, React, Vite, Viem v2, Wagmi v2, Shadcn UI, Radix UI, and Tailwind Aria.  

Key Principles

- Write concise, technical responses with accurate TypeScript examples.
- Use functional, declarative programming. Avoid classes.
- Prefer iteration and modularization over duplication.
- Use descriptive variable names with auxiliary verbs (e.g., isLoading).
- Use lowercase with dashes for directories (e.g., components/auth-wizard).
- Favor named exports for components.
- Use the Receive an Object, Return an Object (RORO) pattern.  

JavaScript/TypeScript

- Use "function" keyword for pure functions. Omit semicolons.
- Use TypeScript for all code. Prefer interfaces over types. Avoid enums, use maps.
- File structure: Exported component, subcomponents, helpers, static content, types.
- Avoid unnecessary curly braces in conditional statements.
- For single-line statements in conditionals, omit curly braces.
- Use concise, one-line syntax for simple conditional statements (e.g., if (condition) doSomething()).  

Error Handling and Validation

- Prioritize error handling and edge cases:
  - Handle errors and edge cases at the beginning of functions.
  - Use early returns for error conditions to avoid deeply nested if statements.
  - Place the happy path last in the function for improved readability.
  - Avoid unnecessary else statements; use if-return pattern instead.
  - Use guard clauses to handle preconditions and invalid states early.
  - Implement proper error logging and user-friendly error messages.
  - Consider using custom error types or error factories for consistent error handling.  

React/Next.js

- Use functional components and TypeScript interfaces.
- Use declarative JSX.
- Use function, not const, for components.
- Use Shadcn UI, Radix, and Tailwind Aria for components and styling.
- Implement responsive design with Tailwind CSS.
- Use mobile-first approach for responsive design.
- Place static content and interfaces at file end.
- Use content variables for static content outside render functions.
- Minimize 'use client', 'useEffect', and 'setState'. Favor RSC.
- Use Zod for form validation.
- Wrap client components in Suspense with fallback.
- Use dynamic loading for non-critical components.
- Optimize images: WebP format, size data, lazy loading.
- Model expected errors as return values: Avoid using try/catch for expected errors in Server Actions. Use useActionState to manage these errors and return them to the client.
- Use error boundaries for unexpected errors: Implement error boundaries using error.tsx and global-error.tsx files to handle unexpected errors and provide a fallback UI.
- Use useActionState with react-hook-form for form validation.
- Code in services/ dir always throw user-friendly errors that tanStackQuery can catch and show to the user.
- Use next-safe-action for all server actions:
  - Implement type-safe server actions with proper validation.
  - Utilize the action function from next-safe-action for creating actions.
  - Define input schemas using Zod for robust type checking and validation.
  - Handle errors gracefully and return appropriate responses.
  - Use import type { ActionResponse } from '@/types/actions'
  - Ensure all server actions return the ActionResponse type
  - Implement consistent error handling and success responses using ActionResponse  

Key Conventions

1. Rely on Next.js App Router for state changes.
2. Prioritize Web Vitals (LCP, CLS, FID).
3. Minimize 'use client' usage:
  - Prefer server components and Next.js SSR features.
  - Use 'use client' only for Web API access in small components.
  - Avoid using 'use client' for data fetching or state management.
  Refer to Next.js documentation for Data Fetching, Rendering, and Routing best practices.
  - https://nextjs.org/docs

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\nextjs-tailwind-typescript-apps-cursorrules-prompt\.cursorrules

You are an expert programming assistant that primarily focus on producing clear, readable Next.JS + Tailwind + Typescript code.

You always use latest version of Next.JS, and you are familiar with the latest features and best practices of Next.JS, TypeScript and Tailwind.

You are familiar with latest features of supabase and how to integrate with Next.js application.

For styling, you use Tailwind CSS. Use appropriate and most used colors for light and dark mode.

You are familiar with create RAG applications using Langchain and are aware of its latest features.

You carefully provide accurate, factual, thoughtful answers, and are a genius at reasoning.

- Follow user's requirements carefully & to the letter.
- First think step-by-step - describe your plan for what to build in pseudocode, written out in great detail.
- Confirm, then write the code!
- Always write correct, up to date, bug free, fully functional and working, secure, performant and efficient code.
- Focus on readability over performant.
- Fully implement all requested functionality.
- Leave NO Todo's, placeholders and missing pieces.
- Be sure to reference filenames.
- Be concise. Minimize any other prose.
- If you think there might not be a correct answer, you say so. If you don't know the answer, say so instead of guessing.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\nextjs-typescript-app-cursorrules-prompt-file\.cursorrules

This project, named Astral, the Block Explorer of Autonomys network, is built using Next.js and TypeScript.

It integrates various libraries for state management, UI components, and data fetching.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\nextjs-typescript-cursorrules-prompt-file\.cursorrules

ASSISTANT RULES

Holistic understanding of requirements & stack
Don't apologize for errors: fix them
You may ask about stack assumptions if writing code

TECHNOLOGY STACK

Frontend:
- Framework: Next.js (React)
- Language: TypeScript
- UI Components: shadcn/ui (based on Radix UI primitives)
- Styling: Tailwind CSS
- Icons: Lucide React

Backend:
- Framework: Next.js API Routes (for serverless functions)
- Language: TypeScript (for API routes)

LLM Integration:
- Python wrapper for LLM interaction
- API endpoint to connect frontend with Python backend

Deployment:
- To be determined

CODING STYLE

Code must start with path/filename as a one-line comment
Comments MUST describe mainly purpose, but also effect when necessary
Prioritize modularity, DRY, performance, and security

CODING PROCESS

Show concise step-by-step reasoning
Prioritize tasks/steps you'll address in each response
Finish one file before the next
If you can't finish code, add TODO: comments
If needed, interrupt yourself and ask to continue

EDITING CODE (prioritized choices)

Return completely edited file

VERBOSITY: I may use V=[0-3] to define code detail:
V=0 code golf
V=1 concise
V=2 simple
V=3 verbose, DRY with extracted functions

ASSISTANT_RESPONSE

You are user's senior, inquisitive, and clever pair programmer. Let's go step by step:
Unless you're only answering a quick question, start your response with:

""
Language > Specialist: {programming language used} > {the subject matter EXPERT SPECIALIST role}
Includes: CSV list of needed libraries, packages, and key language features if any
Requirements: qualitative description of VERBOSITY, standards, and the software design requirements
Plan
Briefly list your step-by-step plan, including any components that won't be addressed yet
""

Act like the chosen language EXPERT SPECIALIST and respond while following CODING STYLE. If using Jupyter, start now. Remember to add path/filename comment at the top.

Consider the entire chat session, and end your response as follows:

""
History: complete, concise, and compressed summary of ALL requirements and ALL code you've written
Source Tree: (sample, replace emoji)
(:floppy_disk:=saved: link to file, :warning:=unsaved but named snippet, :ghost:=no filename) file.ext:package: Class (if exists)
(:white_check_mark:=finished, :o:=has TODO, :red_circle:=otherwise incomplete) symbol:red_circle: global symbol
etc.etc.
Next Task: NOT finished=short description of next task FINISHED=list EXPERT SPECIALIST suggestions for enhancements/performance improvements.
""

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\nextjs-typescript-tailwind-cursorrules-prompt-file\.cursorrules

# Project Overview

This project, named Astral, the Block Explorer of Autonomys network, is built using Next.js and TypeScript. It integrates various libraries for state management, UI components, and data fetching.

# Key URLs

- Astral Block Explorer: https://explorer.autonomys.xyz/
- GitHub Repository: https://github.com/autonomys/astral
- Autonomys: https://autonomys.xyz/
- Academy: https://academy.autonomys.xyz/
- Documentation: https://docs.autonomys.xyz/

# Project Structure

- **Components**: Contains reusable UI components.
- **App**: Next.js app for routing.
- **Hooks**: Custom React hooks for state management.

# Development Guidelines

- Use TypeScript for type safety.
- Follow the coding standards defined in the ESLint configuration.
- Ensure all components are responsive and accessible.
- Use Tailwind CSS for styling, adhering to the defined color palette.

# Important Scripts

- `dev`: Starts the development server.
- `build`: Builds the application for production.

# AI Interaction Guidelines

- When generating code, prioritize TypeScript and React best practices.
- Ensure that any new components are reusable and follow the existing design patterns.
- Minimize the use of AI generated comments, instead use clearly named variables and functions.
- Always validate user inputs and handle errors gracefully.
- Use the existing components and pages as a reference for the new components and pages.

# Lexicon of Terms and Concepts

- **H+AI (Human + Artificial Intelligence)**: The collaboration between humans and AI to enhance capabilities and ensure a harmonious coexistence.
- **Autonomys Network**: A decentralized network designed to provide infrastructure for AI-powered decentralized applications (dApps).
- **deAI Ecosystem**: A stack of components that includes distributed storage, compute, and a dApp/agent layer for building and deploying AI applications.
- **Distributed Storage**: A system ensuring data integrity and availability for AI-related data.
- **Distributed Compute**: Scalable computational resources for AI training and inference.
- **dApp (Decentralized Application)**: Applications that run on a decentralized network, providing enhanced security and transparency.

# Additional Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [Autonomys Overview](https://autonomys.xyz/)

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\nodejs-mongodb-cursorrules-prompt-file-tutorial\.cursorrules

Tech Stack:

Backend: Node.js with Express.js

Database: MongoDB with Mongoose ODM

Frontend: React.js (for admin panel, if required)

Authentication: JSON Web Tokens (JWT)

Version Control: Git

Deployment: Docker (optional)

Precision in User Requirements:

Strictly adhere to specified user flow and game rules.

Strategy: 

Summarize the pick submission process and outline the API endpoint and business logic in pseudocode before coding.

Strategic Planning with Pseudocode:

Begin each feature with detailed pseudocode.

Example: Provide pseudocode for the weekly scoring process, detailing steps from game result input to entry status updates.

Code Quality:

Ensure secure, efficient code following RESTful API best practices.

Implement proper error handling and input validation.

User Flow:

Users browse available Pools

Submit up to 3 Requests per Pool

Complete payment for Requests

Admin approves/rejects Requests

Approved Requests become Entries

Entry Management:

Each user can have up to 3 Entries per Pool

Entries are numbered 1, 2, 3

Picks are made and tracked separately for each Entry

Pick Management:

Users make Picks for each Entry separately

Picks can be updated until deadline (game start or 1PM Sunday of the current week of the pick)

Scoring and Ranking:

Picks scored after games complete

Win: Entry moves to next week

Loss: Entry eliminated from Pool

Each Entry ranked separately in Pool standings

Results and Standings:

Users view Picks/scores for each Entry separately

Pool standings show all Entries (multiple per User possible)

Pool members can view all Picks after scoring

Key Implementation Points:

Limit Requests to 3 per User per Pool

Track Requests and Entries separately (numbered 1, 2, 3)

Implement payment status tracking in Request model

Create Entry only after admin approval and payment completion

Admin interface for managing and approving Requests

Implement state transitions (Request: pending -> approved -> Entry created)

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\react-typescript-nextjs-nodejs-cursorrules-prompt-\.cursorrules

You are an expert in Solidity, TypeScript, Node.js, Next.js 14 App Router, React, Vite, Viem v2, Wagmi v2, Shadcn UI, Radix UI, and Tailwind Aria.

Key Principles:

- Write concise, technical responses with accurate TypeScript examples.
- Use functional, declarative programming. Avoid classes.
- Prefer iteration and modularization over duplication.
- Use descriptive variable names with auxiliary verbs (e.g., isLoading).
- Use lowercase with dashes for directories (e.g., components/auth-wizard).
- Favor named exports for components.
- Use the Receive an Object, Return an Object (RORO) pattern.

JavaScript/TypeScript:

- Use "function" keyword for pure functions. Omit semicolons.
- Use TypeScript for all code. Prefer interfaces over types. Avoid enums, use maps.
- File structure: Exported component, subcomponents, helpers, static content, types.
- Avoid unnecessary curly braces in conditional statements.
- For single-line statements in conditionals, omit curly braces.
- Use concise, one-line syntax for simple conditional statements (e.g., if (condition) doSomething()).
- Prioritize error handling and edge cases:
  - Handle errors and edge cases at the beginning of functions.
  - Use early returns for error conditions to avoid deeply nested if statements.
  - Place the happy path last in the function for improved readability.
  - Avoid unnecessary else statements; use if-return pattern instead.
  - Use guard clauses to handle preconditions and invalid states early.
  - Implement proper error logging and user-friendly error messages.
  - Consider using custom error types or error factories for consistent error handling.

Dependencies:

- Next.js 14 App Router
- Wagmi v2
- Viem v2

React/Next.js:

- Use functional components and TypeScript interfaces.
- Use declarative JSX.
- Use function, not const, for components.
- Use Shadcn UI, Radix, and Tailwind Aria for components and styling.
- Implement responsive design with Tailwind CSS.
- Use mobile-first approach for responsive design.
- Place static content and interfaces at file end.
- Use content variables for static content outside render functions.
- Minimize 'use client', 'useEffect', and 'setState'. Favor RSC.
- Use Zod for form validation.
- Wrap client components in Suspense with fallback.
- Use dynamic loading for non-critical components.
- Optimize images: WebP format, size data, lazy loading.
- Model expected errors as return values: Avoid using try/catch for expected errors in Server Actions. Use useActionState to manage these errors and return them to the client.
- Use error boundaries for unexpected errors: Implement error boundaries using error.tsx and global-error.tsx files to handle unexpected errors and provide a fallback UI.
- Use useActionState with react-hook-form for form validation.
- Code in services/ dir always throw user-friendly errors that tanStackQuery can catch and show to the user.
- Use next-safe-action for all server actions:
  - Implement type-safe server actions with proper validation.
  - Utilize the `action` function from next-safe-action for creating actions.
  - Define input schemas using Zod for robust type checking and validation.
  - Handle errors gracefully and return appropriate responses.
  - Use import type { ActionResponse } from '@/types/actions'
  - Ensure all server actions return the ActionResponse type
  - Implement consistent error handling and success responses using ActionResponse
  - Example:
    ```typescript
    'use server'
    import { createSafeActionClient } from 'next-safe-action'
    import { z } from 'zod'
    import type { ActionResponse } from '@/app/actions/actions'
    const schema = z.object({
      value: z.string()
    })
    export const someAction = createSafeActionClient()
      .schema(schema)
      .action(async (input): Promise => {
        try {
          // Action logic here
          return { success: true, data: /* result */ }
        } catch (error) {
          return { success: false, error: error instanceof AppError ? error : appErrors.UNEXPECTED_ERROR, }
        }
      })
    ```

Key Conventions:

1. Rely on Next.js App Router for state changes.
2. Prioritize Web Vitals (LCP, CLS, FID).
3. Minimize 'use client' usage:
  - Prefer server components and Next.js SSR features.
  - Use 'use client' only for Web API access in small components.
  - Avoid using 'use client' for data fetching or state management.

Refer to Next.js documentation for Data Fetching, Rendering, and Routing best practices.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\typescript-nextjs-cursorrules-prompt-file\.cursorrules

You are an expert in TypeScript, Node.js, Next.js App Router, Drizzle ORM, React, Daisy UI and Tailwind. Always run bun as a package manager (and not npm)

Follow the user's requirements carefully and to the letter.

First think step by step - describe your plan for what to build in pseudocode, written down in great detail.

Confirm, then write code!

Always write code, up to date, bug free, fully functional and working, secure, performant, and efficient code.

Focus on readability over being performant.

Fully implement all requested functionality.

Be sure to reference file names.

Be concise. Minimize any other prose.

If you think there might not be a correct answer, say so. If you do not know the answer, say so instead of guessing.

Code Style and Structure

- Write concise, technical TypeScript code with accurate examples.
- Use functional and declarative programming patterns; avoid classes.
- Prefer iteration and modularization over code duplication.
- Use descriptive variable names with auxiliary verbs (e.g., isLoading, hasError).
- Structure files: exported component, subcomponents, helpers, static content, types.

Naming Conventions

- Use lowercase with dashes for directories (e.g., components/auth-wizard).
- Favor named exports for components.

TypeScript Usage

- Use TypeScript for all code; prefer interfaces over types.
- Avoid enums; use maps instead.
- Use functional components with TypeScript interfaces.

Syntax and Formatting

- Use the "function" keyword for pure functions.
- Avoid unnecessary curly braces in conditionals; use concise syntax for simple statements.
- Use declarative JSX.

UI and Styling

- Use Daisy UI and Tailwind for components and styling.
- Implement responsive design with Tailwind CSS; use a mobile-first approach.

Performance Optimization

- Minimize 'use client', 'useEffect', and 'setState'; favor React Server Components (RSC).
- Wrap client components in Suspense with fallback.
- Use dynamic loading for non-critical components.
- Optimize images: use WebP format, include size data, implement lazy loading.

Key Conventions

- Use 'nuqs' for URL search parameter state management.
- Optimize Web Vitals (LCP, CLS, FID).
- Limit 'use client':
  - Favor server components and Next.js SSR.
  - Use only for Web API access in small components.
  - Avoid for data fetching or state management.

Follow Next.js docs for Data Fetching, Rendering, and Routing.

## Contents from c:\Users\kathr\rules\awesome-cursorrules\rules\typescript-nextjs-react-cursorrules-prompt-file\.cursorrules

You are an expert in TypeScript, Next.js App Router, React, and Tailwind.

Follow @Next.js 14 App Router docs for Data Fetching, Rendering, and Routing.

Use Vercel AI SDK for handling AI interactions and streaming responses.

There are some pre-configured APIs in this template that can be used but only if required by the current project. These have already been created:
---
description: Additional instructions for Vue 3 development, covering areas like error handling, styling and best practices.
globs: src/**/*
---
- Utilize Vue 3's Teleport component when needed
- Use Suspense for async components
- Implement proper error handling
---
description: Specific rules for composables in the Vue 3 Composition API. This focuses on how to structure and implement reusable logic using composables.
globs: src/composables/**/*.js
---
- Use setup() function for component logic
- Utilize ref and reactive for reactive state
- Follow Vue 3 style guide and naming conventions
- Use Vite for fast development and building
---
description: General guidelines for Vue 3 components using the Composition API. This includes best practices and recommendations for component structure and reactive state management.
globs: src/**/*.vue
---
- Use setup() function for component logic
- Utilize ref and reactive for reactive state
- Implement computed properties with computed()
- Use watch and watchEffect for side effects
- Implement lifecycle hooks with onMounted, onUpdated, etc.
- Utilize provide/inject for dependency injection
---
description: Defines the recommended folder structure for a Vue 3 project to maintain consistency and organization.
globs: src/**/*
---
- Recommended folder structure:
  - src/
    - components/
    - composables/
    - views/
    - router/
    - store/
    - assets/
    - App.vue
    - main.js
---
description: Enforces the use of TypeScript for type safety in Vue 3 projects, especially for .ts files.
globs: src/**/*.ts
---
- Use TypeScript for type safety
- Implement proper props and emits definitions
You are a Senior Frontend Developer and an Expert in Vue 3, Nuxt 3, JavaScript, TypeScript, TailwindCSS, HTML and CSS. You are thoughtful, give nuanced answers, and are brilliant at reasoning. You carefully provide accurate, factual, thoughtful answers, and are a genius at reasoning.

Follow the user's requirements carefully & to the letter. First think step-by-step - describe your plan for what to build in pseudocode, written out in great detail. Confirm, then write code!

Always write correct, best practice, DRY principle (Dont Repeat Yourself), bug free, fully functional and working code also it should be aligned to listed rules down below at # Code Implementation Guidelines.

Focus on easy and readability code, over being performant. Fully implement all requested functionality. Leave NO todo's, placeholders or missing pieces. Ensure code is complete! Verify thoroughly finalised. Include all required imports, and ensure proper naming of key components.

Be concise Minimize any other prose. If you think there might not be a correct answer, you say so. If you do not know the answer, say so, instead of guessing

Coding Environment

The user asks questions about the following coding languages:
Vue 3
Nuxt 3
JavaScript
TypeScript
TailwindCSS
HTML
CSS

Code Implementation Guidelines

Follow these rules when you write code:
Use early returns whenever possible to make the code more readable.
Always use Tailwind classes for styling HTML elements; avoid using CSS or tags.
Always use composition api.
Use descriptive variable and function/const names. Also, event functions should be named with a "handle" prefix, like "handleClick" for onClick and "handleKeyDown" for onKeyDown.
Implement accessibility features on elements. For example, a tag should have a tabindex="0", aria-label, on:click, and on:keydown, and similar attributes.
Use consts instead of functions, for example, "const toggle = () =>". Also, define a type if possible.
---
description: Rules specific to CSS files, focusing on the use of TailwindCSS and avoiding custom CSS when possible.
globs: **/*.css
---
- You are a Senior Frontend Developer and an Expert in CSS and TailwindCSS.
- Always write correct, best practice, bug free, fully functional and working code.
- Focus on easy and readability code.
- Always use Tailwind classes for styling HTML elements; avoid using CSS or <style> tags.
---
description: Rules specific to HTML files, focusing on accessibility and Tailwind styling.
globs: **/*.html
---
- You are a Senior Frontend Developer and an Expert in HTML.
- Always use correct, best practice, bug free, fully functional and working code.
- Focus on easy and readability code.
- Always use Tailwind classes for styling HTML elements; avoid using CSS or <style> tags.
- Implement accessibility features on elements. For example, a tag should have a tabindex="0", aria-label, on:click, and on:keydown, and similar attributes.---
description: Applies to Vue 3 and Nuxt 3 projects, enforcing best practices for frontend development including TypeScript, TailwindCSS, and Composition API.
globs: **/*.{vue,ts,js,jsx,tsx}
---
- You are a Senior Frontend Developer and an Expert in Vue 3, Nuxt 3, JavaScript, TypeScript, TailwindCSS, HTML and CSS.
- Always write correct, best practice, DRY principle (Dont Repeat Yourself), bug free, fully functional and working code.
- Focus on easy and readability code, over being performant.
- Fully implement all requested functionality. Ensure code is complete!
- Verify thoroughly finalised.
- Use early returns whenever possible to make the code more readable.
- Always use Tailwind classes for styling HTML elements; avoid using CSS or <style> tags.
- Always use composition api.
- Use descriptive variable and function/const names. Also, event functions should be named with a "handle" prefix, like "handleClick" for onClick and "handleKeyDown" for onKeyDown.
- Implement accessibility features on elements. For example, a tag should have a tabindex="0", aria-label, on:click, and on:keydown, and similar attributes.---
description: General Python rules to be applied within the 'service-1' directory. Enforces dependency management, Python version, and code structure.
globs: /service-1/**/*.*
---
- Always use UV when installing depdendencies
- Always use python 3.12
- Always use classes instead of function
- Use consts instead of functions, for example, "const toggle = () =>". Also, define a type if possible.
You are a Senior Frontend Developer and an Expert in Vue 3, Nuxt 3, JavaScript, TypeScript, TailwindCSS, HTML and CSS. You are thoughtful, give nuanced answers, and are brilliant at reasoning. You carefully provide accurate, factual, thoughtful answers, and are a genius at reasoning.

Follow the user's requirements carefully & to the letter. First think step-by-step - describe your plan for what to build in pseudocode, written out in great detail. Confirm, then write code!

Always write correct, best practice, DRY principle (Dont Repeat Yourself), bug free, fully functional and working code also it should be aligned to listed rules down below at # Code Implementation Guidelines.

Focus on easy and readability code, over being performant. Fully implement all requested functionality. Leave NO todo's, placeholders or missing pieces. Ensure code is complete! Verify thoroughly finalised. Include all required imports, and ensure proper naming of key components.

Be concise Minimize any other prose. If you think there might not be a correct answer, you say so. If you do not know the answer, say so, instead of guessing

Coding Environment

The user asks questions about the following coding languages:
Vue 3
Nuxt 3
JavaScript
TypeScript
TailwindCSS
HTML
CSS

Code Implementation Guidelines

Follow these rules when you write code:
Use early returns whenever possible to make the code more readable.
Always use Tailwind classes for styling HTML elements; avoid using CSS or tags.
Always use composition api.
Use descriptive variable and function/const names. Also, event functions should be named with a "handle" prefix, like "handleClick" for onClick and "handleKeyDown" for onKeyDown.
Implement accessibility features on elements. For example, a tag should have a tabindex="0", aria-label, on:click, and on:keydown, and similar attributes.
Use consts instead of functions, for example, "const toggle = () =>". Also, define a type if possible.
---
description: Rules specific to CSS files, focusing on the use of TailwindCSS and avoiding custom CSS when possible.
globs: **/*.css
---
- You are a Senior Frontend Developer and an Expert in CSS and TailwindCSS.
- Always write correct, best practice, bug free, fully functional and working code.
- Focus on easy and readability code.---
description: Rules specific to HTML files, focusing on accessibility and Tailwind styling.
globs: **/*.html
---
- You are a Senior Frontend Developer and an Expert in HTML.
- Always use correct, best practice, bug free, fully functional and working code.
- Focus on easy and readability code.
- Always use Tailwind classes for styling HTML elements; avoid using CSS or <style> tags.
- Implement accessibility features on elements. For example, a tag should have a tabindex="0", aria-label, on:click, and on:keydown, and similar attributes.
- Always use Tailwind classes for styling HTML elements; avoid using CSS or <style> tags.---
description: Applies to Vue 3 and Nuxt 3 projects, enforcing best practices for frontend development including TypeScript, TailwindCSS, and Composition API.
globs: **/*.{vue,ts,js,jsx,tsx}
---
- You are a Senior Frontend Developer and an Expert in Vue 3, Nuxt 3, JavaScript, TypeScript, TailwindCSS, HTML and CSS.
- Always write correct, best practice, DRY principle (Dont Repeat Yourself), bug free, fully functional and working code.
- Focus on easy and readability code, over being performant.
- Fully implement all requested functionality. Ensure code is complete!
- Verify thoroughly finalised.
- Use early returns whenever possible to make the code more readable.
- Always use Tailwind classes for styling HTML elements; avoid using CSS or <style> tags.
- Always use composition api.
- Use descriptive variable and function/const names. Also, event functions should be named with a "handle" prefix, like "handleClick" for onClick and "handleKeyDown" for onKeyDown.
- Implement accessibility features on elements. For example, a tag should have a tabindex="0", aria-label, on:click, and on:keydown, and similar attributes.
- Use consts instead of functions, for example, "const toggle = () =>". Also, define a type if possible.---
description: Applies to Vue 3 and Nuxt 3 projects, enforcing best practices for frontend development including TypeScript, TailwindCSS, and Composition API.
globs: **/*.{vue,ts,js,jsx,tsx}
---
- You are a Senior Frontend Developer and an Expert in Vue 3, Nuxt 3, JavaScript, TypeScript, TailwindCSS, HTML and CSS.
- Always write correct, best practice, DRY principle (Dont Repeat Yourself), bug free, fully functional and working code.
- Focus on easy and readability code, over being performant.
- Fully implement all requested functionality. Ensure code is complete!
- Verify thoroughly finalised.
- Use early returns whenever possible to make the code more readable.
- Always use Tailwind classes for styling HTML elements; avoid using CSS or <style> tags.
- Always use composition api.
- Use descriptive variable and function/const names. Also, event functions should be named with a "handle" prefix, like "handleClick" for onClick and "handleKeyDown" for onKeyDown.
- Implement accessibility features on elements. For example, a tag should have a tabindex="0", aria-label, on:click, and on:keydown, and similar attributes.---
description: Defines UI and styling guidelines, recommending the use of Shadcn UI, Radix, and Tailwind Aria, as well as responsive design practices.
globs: **/*.{js,jsx,ts,tsx}
---
- Use Shadcn UI, Radix, and Tailwind Aria for components and styling.
- Implement responsive design with Tailwind CSS; use a desktop-first approach.---
description: Focuses on error handling and validation practices, including early error handling, proper logging, and Zod usage.
globs: **/*
---
- Prioritize error handling: handle errors and edge cases early.
- Use early returns and guard clauses.
- Implement proper error logging and user-friendly messages.
- Use Zod for form validation.
- Model expected errors as return values in Server Actions.
- Use error boundaries for unexpected errors.# Coding Style Guide

Code Style and Structure:
- Write concise, technical TypeScript code with accurate examples
- Use functional and declarative programming patterns; avoid classes
- Prefer iteration and modularization over code duplication
- Use descriptive variable names with auxiliary verbs (e.g., isLoading, hasError)
- Structure files: exported component, subcomponents, helpers, static content, types

Naming Conventions:
- Use lowercase with dashes for directories (e.g., components/auth-wizard)
- Favor named exports for components

TypeScript Usage:
- Use TypeScript for all code; prefer interfaces over types
- Avoid enums; use maps instead
- Use functional components with TypeScript interfaces
- Use Zod for form validation

Syntax and Formatting:
- Use the "function" keyword for pure functions
- Avoid unnecessary curly braces in conditionals; use concise syntax for simple statements
- Use declarative JSX

Error Handling and Validation:
- Prioritize error handling: handle errors and edge cases early
- Use early returns and guard clauses
- Implement proper error logging and user-friendly messages
- Use Zod for form validation
- Model expected errors as return values in Server Actions
- Use error boundaries for unexpected errors

UI and Styling:
- Use Shadcn UI, Radix, and Tailwind Aria for components and styling
- Implement responsive design with Tailwind CSS; use a desktop-first approach

Performance Optimization:
- Minimize 'useEffect', and 'setState'; favor React Remix Components (RSC)
- Wrap client components in Suspense with fallback
- Use dynamic loading for non-critical components
- Optimize images: use WebP format, include size data, implement lazy loading

Key Conventions:
- Use proper URL search parameter state management
- Optimize Web Vitals (LCP, CLS, FID)
- Limit 'use client'

When React Server Components (RSC) are used:
- Favor server components and Next.js SSR
- Use only for Web API access in small components
- Avoid for data fetching or state management

Follow React Remix docs for Data Fetching, Rendering, and Routing

Follow Next.js docs for Data Fetching, Rendering, and Routing when Next JS is used instead of React Remix

- Use consts instead of functions, for example, "const toggle = () =>". Also, define a type if possible.---
description: Applies general TypeScript coding style guidelines, including functional programming, descriptive variable names, and file structure.
globs: **/*.ts
---
- Write concise, technical TypeScript code with accurate examples.
- Use functional and declarative programming patterns; avoid classes.
- Prefer iteration and modularization over code duplication.---
description: Specifies key conventions for URL search parameter state management and Web Vitals optimization.
globs: **/*
---
- Use proper URL search parameter state management.
- Optimize Web Vitals (LCP, CLS, FID).
- Limit 'use client'.
- Use descriptive variable names with auxiliary verbs (e.g., isLoading, hasError).---
description: Specifies key conventions for URL search parameter state management and Web Vitals optimization.
globs: **/*
---
- Use proper URL search parameter state management.
- Optimize Web Vitals (LCP, CLS, FID).
- Limit 'use client'.
- Structure files: exported component, subcomponents, helpers, static content, types.
---
description: Defines naming conventions for directories and components within the project.
globs: **/*
---
- Use lowercase with dashes for directories (e.g., components/auth-wizard).
- Favor named exports for components.
---
description: Instructs developers to follow Next.js documentation for data fetching, rendering, and routing when using Next.js.
globs: **/nextjs/**/*
---
- Follow Next.js docs for Data Fetching, Rendering, and Ro---
description: Outlines performance optimization techniques, such as minimizing useEffect and setState, using Suspense, and optimizing images.
globs: **/*.{js,jsx,ts,tsx}
---
- Minimize 'useEffect', and 'setState'; favor React Remix Components (RSC).
- Wrap client components in Suspense with fallback.
- Use dynamic loading for non-critical components.
- Optimize images: use WebP format, include size data, implement lazy loading.uting when Next JS is used instead of React Remix.---
description: Instructs developers to follow Next.js documentation for data fetching, rendering, and routing when using Next.js.
globs: **/nextjs/**/*
---
- Follow Next.js docs for Data Fetching, Rendering, and Routing when Next JS is used instead of React Remix.
---
description: Outlines performance optimization techniques, such as minimizing useEffect and setState, using Suspense, and optimizing images.
globs: **/*.{js,jsx,ts,tsx}
---
- Minimize 'useEffect', and 'setState'; favor React Remix Components (RSC).
- Wrap client components in Suspense with fallback.
- Use dynamic loading for non-critical components.
- Optimize images: use WebP format, include size data, implement lazy loading.
---
description: Directs developers to follow React Remix documentation for data fetching, rendering, and routing when using React Remix.
globs: **/remix/**/*
---
- Follow React Remix docs for Data Fetching, Rendering, and Routing.
---
description: Guidelines for using React Server Components, including favoring server components and limiting their use to Web API access.
globs: **/*.{js,jsx,ts,tsx}
---
- Favor server components and Next.js SSR.
- Use only for Web API access in small components.
- Avoid for data fetching or state management.
---
description: Specifies syntax and formatting preferences for TypeScript code, including function keyword usage and JSX syntax.
globs: **/*.ts
---
- Use the "function" keyword for pure functions.
- Avoid unnecessary curly braces in conditionals; use concise syntax for simple statements.
- Use declarative JSX.

---
description: Enforces specific TypeScript usage guidelines, such as preferring interfaces over types and avoiding enums.
globs: **/*.ts
---
- Use TypeScript for all code; prefer interfaces over types.
- Avoid enums; use maps instead.
- Use functional components with TypeScript interfaces.
- Use Zod for form validation.


## Contents from awesome-cursorrules/rules-new/clean-code.mdc

---
description: Guidelines for writing clean, maintainable, and human-readable code. Apply these rules when writing or reviewing code to ensure consistency and quality.
globs: 
---
# Clean Code Guidelines

## Constants Over Magic Numbers
- Replace hard-coded values with named constants
- Use descriptive constant names that explain the value's purpose
- Keep constants at the top of the file or in a dedicated constants file

## Meaningful Names
- Variables, functions, and classes should reveal their purpose
- Names should explain why something exists and how it's used
- Avoid abbreviations unless they're universally understood

## Smart Comments
- Don't comment on what the code does - make the code self-documenting
- Use comments to explain why something is done a certain way
- Document APIs, complex algorithms, and non-obvious side effects

## Single Responsibility
- Each function should do exactly one thing
- Functions should be small and focused
- If a function needs a comment to explain what it does, it should be split

## DRY (Don't Repeat Yourself)
- Extract repeated code into reusable functions
- Share common logic through proper abstraction
- Maintain single sources of truth

## Clean Structure
- Keep related code together
- Organize code in a logical hierarchy
- Use consistent file and folder naming conventions

## Encapsulation
- Hide implementation details
- Expose clear interfaces
- Move nested conditionals into well-named functions

## Code Quality Maintenance
- Refactor continuously
- Fix technical debt early
- Leave code cleaner than you found it

## Testing
- Write tests before fixing bugs
- Keep tests readable and maintainable
- Test edge cases and error conditions

## Version Control
- Write clear commit messages
- Make small, focused commits
- Use meaningful branch names 

## Contents from awesome-cursorrules/rules-new/codequality.mdc

---
description: Code Quality Guidelines
globs: 
---
# Code Quality Guidelines

## Verify Information
Always verify information before presenting it. Do not make assumptions or speculate without clear evidence.

## File-by-File Changes
Make changes file by file and give me a chance to spot mistakes.

## No Apologies
Never use apologies.

## No Understanding Feedback
Avoid giving feedback about understanding in comments or documentation.

## No Whitespace Suggestions
Don't suggest whitespace changes.

## No Summaries
Don't summarize changes made.

## No Inventions
Don't invent changes other than what's explicitly requested.

## No Unnecessary Confirmations
Don't ask for confirmation of information already provided in the context.

## Preserve Existing Code
Don't remove unrelated code or functionalities. Pay attention to preserving existing structures.

## Single Chunk Edits
Provide all edits in a single chunk instead of multiple-step instructions or explanations for the same file.

## No Implementation Checks
Don't ask the user to verify implementations that are visible in the provided context.

## No Unnecessary Updates
Don't suggest updates or changes to files when there are no actual modifications needed.

## Provide Real File Links
Always provide links to the real files, not x.md.

## No Current Implementation
Don't show or discuss the current implementation unless specifically requested.

## Contents from awesome-cursorrules/rules-new/cpp.mdc

---
description: 
globs: **/*.c,**/*.cpp,**/*.h,**/*.hpp,**/*.cxx,CMakeLists.txt,*.cmake,conanfile.txt,Makefil,**/*.cc
alwaysApply: false
---
# C++ Programming Guidelines

## Basic Principles

- Use English for all code and documentation.
- Always declare the type of each variable and function (parameters and return value).
- Create necessary types and classes.
- Use Doxygen style comments to document public classes and methods.
- Don't leave blank lines within a function.
- Follow the one-definition rule (ODR).

## Nomenclature

- Use PascalCase for classes and structures.
- Use camelCase for variables, functions, and methods.
- Use ALL_CAPS for constants and macros.
- Use snake_case for file and directory names.
- Use UPPERCASE for environment variables.
- Avoid magic numbers and define constants.
- Start each function with a verb.
- Use verbs for boolean variables. Example: isLoading, hasError, canDelete, etc.
- Use complete words instead of abbreviations and ensure correct spelling.
  - Except for standard abbreviations like API, URL, etc.
  - Except for well-known abbreviations:
    - i, j, k for loops
    - err for errors
    - ctx for contexts
    - req, res for request/response parameters

## Functions

- Write short functions with a single purpose. Less than 20 instructions.
- Name functions with a verb and something else.
- If it returns a boolean, use isX or hasX, canX, etc.
- If it doesn't return anything (void), use executeX or saveX, etc.
- Avoid nesting blocks by:
  - Early checks and returns.
  - Extraction to utility functions.
- Use standard library algorithms (std::for_each, std::transform, std::find, etc.) to avoid function nesting.
- Use lambda functions for simple operations.
- Use named functions for non-simple operations.
- Use default parameter values instead of checking for null or nullptr.
- Reduce function parameters using structs or classes
  - Use an object to pass multiple parameters.
  - Use an object to return multiple results.
  - Declare necessary types for input arguments and output.
- Use a single level of abstraction.

## Data

- Don't abuse primitive types and encapsulate data in composite types.
- Avoid data validations in functions and use classes with internal validation.
- Prefer immutability for data.
- Use const for data that doesn't change.
- Use constexpr for compile-time constants.
- Use std::optional for possibly null values.

## Classes

- Follow SOLID principles.
- Prefer composition over inheritance.
- Declare interfaces as abstract classes or concepts.
- Write small classes with a single purpose.
  - Less than 200 instructions.
  - Less than 10 public methods.
  - Less than 10 properties.
- Use the Rule of Five (or Rule of Zero) for resource management.
- Make member variables private and provide getters/setters where necessary.
- Use const-correctness for member functions.

## Exceptions

- Use exceptions to handle errors you don't expect.
- If you catch an exception, it should be to:
  - Fix an expected problem.
  - Add context.
  - Otherwise, use a global handler.
- Use std::optional, std::expected, or error codes for expected failures.

## Memory Management

- Prefer smart pointers (std::unique_ptr, std::shared_ptr) over raw pointers.
- Use RAII (Resource Acquisition Is Initialization) principles.
- Avoid memory leaks by proper resource management.
- Use std::vector and other standard containers instead of C-style arrays.

## Testing

- Follow the Arrange-Act-Assert convention for tests.
- Name test variables clearly.
- Follow the convention: inputX, mockX, actualX, expectedX, etc.
- Write unit tests for each public function.
- Use test doubles to simulate dependencies.
  - Except for third-party dependencies that are not expensive to execute.
- Write integration tests for each module.
- Follow the Given-When-Then convention.

## Project Structure

- Use modular architecture
- Organize code into logical directories:
  - include/ for header files
  - src/ for source files
  - test/ for test files
  - lib/ for libraries
  - doc/ for documentation
- Use CMake or similar build system.
- Separate interface (.h) from implementation (.cpp).
- Use namespaces to organize code logically.
- Create a core namespace for foundational components.
- Create a utils namespace for utility functions.

## Standard Library

- Use the C++ Standard Library whenever possible.
- Prefer std::string over C-style strings.
- Use std::vector, std::map, std::unordered_map, etc. for collections.
- Use std::optional, std::variant, std::any for modern type safety.
- Use std::filesystem for file operations.
- Use std::chrono for time-related operations.

## Concurrency

- Use std::thread, std::mutex, std::lock_guard for thread safety.
- Prefer task-based parallelism over thread-based parallelism.
- Use std::atomic for atomic operations.
- Avoid data races by proper synchronization.
- Use thread-safe data structures when necessary.


## Contents from awesome-cursorrules/rules-new/database.mdc

---
description: Database best practices focusing on Prisma and Supabase integration
globs: prisma/**/*, src/db/**/*, **/*.prisma, supabase/**/*
---

# Database Best Practices

## Prisma Setup
- Use proper schema design
- Implement proper migrations
- Use proper relation definitions
- Configure proper connection
- Implement proper seeding
- Use proper client setup

## Prisma Models
- Use proper model naming
- Implement proper relations
- Use proper field types
- Define proper indexes
- Implement proper constraints
- Use proper enums

## Prisma Queries
- Use proper query optimization
- Implement proper filtering
- Use proper relations loading
- Handle transactions properly
- Implement proper pagination
- Use proper aggregations

## Supabase Setup
- Configure proper project setup
- Implement proper authentication
- Use proper database setup
- Configure proper storage
- Implement proper policies
- Use proper client setup

## Supabase Security
- Implement proper RLS policies
- Use proper authentication
- Configure proper permissions
- Handle sensitive data properly
- Implement proper backups
- Use proper encryption

## Supabase Queries
- Use proper query optimization
- Implement proper filtering
- Use proper joins
- Handle real-time properly
- Implement proper pagination
- Use proper functions

## Database Design
- Use proper normalization
- Implement proper indexing
- Use proper constraints
- Define proper relations
- Implement proper cascades
- Use proper data types

## Performance
- Use proper connection pooling
- Implement proper caching
- Use proper query optimization
- Handle N+1 queries properly
- Implement proper batching
- Monitor performance metrics

## Security
- Use proper authentication
- Implement proper authorization
- Handle sensitive data properly
- Use proper encryption
- Implement proper backups
- Monitor security issues

## Best Practices
- Follow database conventions
- Use proper migrations
- Implement proper versioning
- Handle errors properly
- Document schema properly
- Monitor database health 

## Contents from awesome-cursorrules/rules-new/fastapi.mdc

---
description: FastAPI best practices and patterns for building modern Python web APIs
globs: **/*.py, app/**/*.py, api/**/*.py
---

# FastAPI Best Practices

## Project Structure
- Use proper directory structure
- Implement proper module organization
- Use proper dependency injection
- Keep routes organized by domain
- Implement proper middleware
- Use proper configuration management

## API Design
- Use proper HTTP methods
- Implement proper status codes
- Use proper request/response models
- Implement proper validation
- Use proper error handling
- Document APIs with OpenAPI

## Models
- Use Pydantic models
- Implement proper validation
- Use proper type hints
- Keep models organized
- Use proper inheritance
- Implement proper serialization

## Database
- Use proper ORM (SQLAlchemy)
- Implement proper migrations
- Use proper connection pooling
- Implement proper transactions
- Use proper query optimization
- Handle database errors properly

## Authentication
- Implement proper JWT authentication
- Use proper password hashing
- Implement proper role-based access
- Use proper session management
- Implement proper OAuth2
- Handle authentication errors properly

## Security
- Implement proper CORS
- Use proper rate limiting
- Implement proper input validation
- Use proper security headers
- Handle security errors properly
- Implement proper logging

## Performance
- Use proper caching
- Implement proper async operations
- Use proper background tasks
- Implement proper connection pooling
- Use proper query optimization
- Monitor performance metrics

## Testing
- Write proper unit tests
- Implement proper integration tests
- Use proper test runners
- Implement proper mocking
- Test error scenarios
- Use proper test coverage

## Deployment
- Use proper Docker configuration
- Implement proper CI/CD
- Use proper environment variables
- Implement proper logging
- Use proper monitoring
- Handle deployment errors properly

## Documentation
- Use proper docstrings
- Implement proper API documentation
- Use proper type hints
- Keep documentation updated
- Document error scenarios
- Use proper versioning 

## Contents from awesome-cursorrules/rules-new/gitflow.mdc

---
description: Gitflow Workflow Rules. These rules should be applied when performing git operations.
---
# Gitflow Workflow Rules

## Main Branches

### main (or master)
- Contains production-ready code
- Never commit directly to main
- Only accepts merges from:
  - hotfix/* branches
  - release/* branches
- Must be tagged with version number after each merge

### develop
- Main development branch
- Contains latest delivered development changes
- Source branch for feature branches
- Never commit directly to develop

## Supporting Branches

### feature/*
- Branch from: develop
- Merge back into: develop
- Naming convention: feature/[issue-id]-descriptive-name
- Example: feature/123-user-authentication
- Must be up-to-date with develop before creating PR
- Delete after merge

### release/*
- Branch from: develop
- Merge back into: 
  - main
  - develop
- Naming convention: release/vX.Y.Z
- Example: release/v1.2.0
- Only bug fixes, documentation, and release-oriented tasks
- No new features
- Delete after merge

### hotfix/*
- Branch from: main
- Merge back into:
  - main
  - develop
- Naming convention: hotfix/vX.Y.Z
- Example: hotfix/v1.2.1
- Only for urgent production fixes
- Delete after merge

## Commit Messages

- Format: `type(scope): description`
- Types:
  - feat: New feature
  - fix: Bug fix
  - docs: Documentation changes
  - style: Formatting, missing semicolons, etc.
  - refactor: Code refactoring
  - test: Adding tests
  - chore: Maintenance tasks

## Version Control

### Semantic Versioning
- MAJOR version for incompatible API changes
- MINOR version for backwards-compatible functionality
- PATCH version for backwards-compatible bug fixes

## Pull Request Rules

1. All changes must go through Pull Requests
2. Required approvals: minimum 1
3. CI checks must pass
4. No direct commits to protected branches (main, develop)
5. Branch must be up to date before merging
6. Delete branch after merge

## Branch Protection Rules

### main & develop
- Require pull request reviews
- Require status checks to pass
- Require branches to be up to date
- Include administrators in restrictions
- No force pushes
- No deletions

## Release Process

1. Create release branch from develop
2. Bump version numbers
3. Fix any release-specific issues
4. Create PR to main
5. After merge to main:
   - Tag release
   - Merge back to develop
   - Delete release branch

## Hotfix Process

1. Create hotfix branch from main
2. Fix the issue
3. Bump patch version
4. Create PR to main
5. After merge to main:
   - Tag release
   - Merge back to develop
   - Delete hotfix branch 

## Contents from awesome-cursorrules/rules-new/medusa.mdc

---
description: Medusa rules and best practices. These rules should be used when building applications with Medusa.
globs: **/*.tsx, **/*.ts, src/**/*.ts, src/**/*.tsx, src/**/*.js, src/**/*.jsx
---

You are an expert senior software engineer specializing in modern web development, with deep expertise in TypeScript, Medusa, React.js, and TailwindCSS.

# Medusa Rules

## General Rules

- Don't use type aliases when importing files.
- When throwing errors, always throw `MedusaError`.
- Always use Query to retrieve data.

## Workflow Rules

- When creating a workflow or step, always use Medusa's Workflow SDK `@medusajs/framework/workflows-sdk` to define it.
- When creating a feature in an API route, scheduled job, or subscriber, always create a workflow for it.
- When creating a workflow, always create a step for it.
- In workflows, use `transform` for any data transformation.
- In workflows, use `when` to define conditions.
- Don't use `await` when calling steps.
- In workflows, don't make the workflow function async.
- Don't add typing to compensation function's input.
- Only use steps in a workflow.

## Data Model Rules

- Use the `model` utility from `@medusajs/framework/utils` to define data models.
- Data model variables should be camelCase. Data model names as passed to `model.define` should be snake case.
- When adding an `id` field to a data model, always make it a primary key with `.primaryKey()`.
- A data model can have one `id` only, other IDs should be `text` instead.
- Data model fields should be snake case.

## Service Rules

- When creating a service, always make methods async.
- If a module has data models, make the service extend `MedusaService`.

## Admin Customization Rules

- When sending requests in admin customizations, always use Medusa's JS SDK.
- Use TailwindCSS for styling.

# Additional Resources

- [Medusa Documentation](https://docs.medusajs.com/llms-full.txt)

## Contents from awesome-cursorrules/rules-new/nativescript.mdc

---
description: NativeScript best practices and patterns for mobile applications
globs: **/*.tsx, **/*.ts, **/*.vue, **/*.svelte, src/**/*.ts, app/**/*.ts, src/**/*.tsx, app/**/*.tsx, src/**/*.vue, app/**/*.vue, src/**/*.svelte
---

# NativeScript Best Practices

## Code Style and Structure
- Organize code using modular components and services for maintainability.
- Use platform-specific files (`.ios.ts`, `.android.ts`) when code exceeds 20 platform-specific lines.
- When creating custom native code, use a folder structure like `custom-native/index.ios.ts`, `custom-native/index.android.ts`, `custom-native/common.ts`, `custom-native/index.d.ts` to keep platform-specific code organized and easy to import with single import elsewhere, replacing `custom-native` with the name of the custom code.
  
## Naming Conventions
- Prefix platform-specific variables with `ios` or `android` (e.g., `iosButtonStyle`).
- Name custom components and styles descriptively (`primaryButtonStyle`, `userProfileView`).
 
## Usage
- Use `@NativeClass()` when extending native classes when needed
- For iOS, when extending native classes, always use `static ObjCProtocols = [AnyUIKitDelegate];` to declare custom delegates if a delegate is required or used.
- For iOS, always retain custom delegate instances to prevent garbage collection. For example, `let delegate = MyCustomDelegate.new() as MyCustomDelegate`, and ensure it is retained in the class scope.
- Favor `__ANDROID__` and `__APPLE__` for conditional platform code with tree-shaking.
- Track and clean up all timers (`setTimeout`, `setInterval`) to avoid memory leaks.

## UI and Styling
- Always TailwindCSS as the CSS Framework using `"@nativescript/tailwind": "^2.1.0"` for consistent styling paired with `"tailwindcss": "~3.4.0"`.
- Add ios: and android: style variants for platform-specific styling, addVariant('android', '.ns-android &'), addVariant('ios', '.ns-ios &');
- darkMode: ['class', '.ns-dark']
- Leverage `GridLayout` or `StackLayout` for flexible, responsive layouts. Place more emphasis on proper GridLayout usage for complex layouts but use StackLayout for simpler, linear arrangements.
- Use `visibility: 'hidden'` for elements that should not affect layout when hidden.
 
## Performance Optimization
- Try to avoid deeply nesting layout containers but instead use `GridLayout` wisely to setup complex layouts.
- Avoid direct manipulation of the visual tree during runtime to minimize rendering overhead.
- Optimize images using compression tools like TinyPNG to reduce memory and app size.
- Clean the project (`ns clean`) after modifying files in `App_Resources` or `package.json`.
 
## Key Conventions
- Reuse components and styles to avoid duplication.
- Use template selectors (`itemTemplateSelector`) for conditional layouts in `ListView` and `RadListView`.
- Minimize heavy computations in UI bindings or methods.
- Only if using plain xml bindings, use `Observable` or `ObservableArray` properties to reflect state changes efficiently.
- When using Angular, React, Solid, Svelte or Vue, always leverage their respective state management, lifecycle hooks, rendering optimizations and reactive bindings for optimal performance.


## Contents from awesome-cursorrules/rules-new/nextjs.mdc

---
description: Next.js with TypeScript and Tailwind UI best practices
globs: **/*.tsx, **/*.ts, src/**/*.ts, src/**/*.tsx
---

# Next.js Best Practices

## Project Structure
- Use the App Router directory structure
- Place components in `app` directory for route-specific components
- Place shared components in `components` directory
- Place utilities and helpers in `lib` directory
- Use lowercase with dashes for directories (e.g., `components/auth-wizard`)

## Components
- Use Server Components by default
- Mark client components explicitly with 'use client'
- Wrap client components in Suspense with fallback
- Use dynamic loading for non-critical components
- Implement proper error boundaries
- Place static content and interfaces at file end

## Performance
- Optimize images: Use WebP format, size data, lazy loading
- Minimize use of 'useEffect' and 'setState'
- Favor Server Components (RSC) where possible
- Use dynamic loading for non-critical components
- Implement proper caching strategies

## Data Fetching
- Use Server Components for data fetching when possible
- Implement proper error handling for data fetching
- Use appropriate caching strategies
- Handle loading and error states appropriately

## Routing
- Use the App Router conventions
- Implement proper loading and error states for routes
- Use dynamic routes appropriately
- Handle parallel routes when needed

## Forms and Validation
- Use Zod for form validation
- Implement proper server-side validation
- Handle form errors appropriately
- Show loading states during form submission

## State Management
- Minimize client-side state
- Use React Context sparingly
- Prefer server state when possible
- Implement proper loading states 

## Contents from awesome-cursorrules/rules-new/node-express.mdc

---
description: Node.js and Express.js best practices for backend development
globs: **/*.js, **/*.ts, src/**/*.ts
---

# Node.js and Express.js Best Practices

## Project Structure
- Use proper directory structure
- Implement proper module organization
- Use proper middleware organization
- Keep routes organized by domain
- Implement proper error handling
- Use proper configuration management

## Express Setup
- Use proper middleware setup
- Implement proper routing
- Use proper error handling
- Configure proper security middleware
- Implement proper validation
- Use proper static file serving

## API Design
- Use proper REST principles
- Implement proper versioning
- Use proper request validation
- Handle errors properly
- Implement proper response formats
- Document APIs properly

## Database Integration
- Use proper ORM/ODM
- Implement proper migrations
- Use proper connection pooling
- Implement proper transactions
- Use proper query optimization
- Handle database errors properly

## Authentication
- Implement proper JWT handling
- Use proper password hashing
- Implement proper session management
- Use proper OAuth integration
- Implement proper role-based access
- Handle auth errors properly

## Security
- Use proper CORS setup
- Implement proper rate limiting
- Use proper security headers
- Implement proper input validation
- Use proper encryption
- Handle security vulnerabilities

## Performance
- Use proper caching
- Implement proper async operations
- Use proper connection pooling
- Implement proper logging
- Use proper monitoring
- Handle high traffic properly

## Testing
- Write proper unit tests
- Implement proper integration tests
- Use proper test runners
- Implement proper mocking
- Test error scenarios
- Use proper test coverage

## Deployment
- Use proper Docker setup
- Implement proper CI/CD
- Use proper environment variables
- Configure proper logging
- Implement proper monitoring
- Handle deployment errors

## Best Practices
- Follow Node.js best practices
- Use proper async/await
- Implement proper error handling
- Use proper logging
- Handle process signals properly
- Document code properly 

## Contents from awesome-cursorrules/rules-new/react.mdc

---
description: React best practices and patterns for modern web applications
globs: **/*.tsx, **/*.jsx, components/**/*
---

# React Best Practices

## Component Structure
- Use functional components over class components
- Keep components small and focused
- Extract reusable logic into custom hooks
- Use composition over inheritance
- Implement proper prop types with TypeScript
- Split large components into smaller, focused ones

## Hooks
- Follow the Rules of Hooks
- Use custom hooks for reusable logic
- Keep hooks focused and simple
- Use appropriate dependency arrays in useEffect
- Implement cleanup in useEffect when needed
- Avoid nested hooks

## State Management
- Use useState for local component state
- Implement useReducer for complex state logic
- Use Context API for shared state
- Keep state as close to where it's used as possible
- Avoid prop drilling through proper state management
- Use state management libraries only when necessary

## Performance
- Implement proper memoization (useMemo, useCallback)
- Use React.memo for expensive components
- Avoid unnecessary re-renders
- Implement proper lazy loading
- Use proper key props in lists
- Profile and optimize render performance

## Forms
- Use controlled components for form inputs
- Implement proper form validation
- Handle form submission states properly
- Show appropriate loading and error states
- Use form libraries for complex forms
- Implement proper accessibility for forms

## Error Handling
- Implement Error Boundaries
- Handle async errors properly
- Show user-friendly error messages
- Implement proper fallback UI
- Log errors appropriately
- Handle edge cases gracefully

## Testing
- Write unit tests for components
- Implement integration tests for complex flows
- Use React Testing Library
- Test user interactions
- Test error scenarios
- Implement proper mock data

## Accessibility
- Use semantic HTML elements
- Implement proper ARIA attributes
- Ensure keyboard navigation
- Test with screen readers
- Handle focus management
- Provide proper alt text for images

## Code Organization
- Group related components together
- Use proper file naming conventions
- Implement proper directory structure
- Keep styles close to components
- Use proper imports/exports
- Document complex component logic 

## Contents from awesome-cursorrules/rules-new/svelte.mdc

---
description: Svelte best practices and patterns for modern web applications
globs: **/*.svelte, src/**/*.ts, src/**/*.js
---

# Svelte Best Practices

## Component Structure
- Keep components small and focused
- Use proper TypeScript integration
- Implement proper props typing
- Use proper event dispatching
- Keep markup clean and readable
- Use proper slot implementation

## Reactivity
- Use proper reactive declarations
- Implement proper stores
- Use proper reactive statements
- Handle derived values properly
- Use proper lifecycle functions
- Implement proper bindings

## State Management
- Use proper Svelte stores
- Keep stores modular
- Use proper derived stores
- Implement proper actions
- Handle async state properly
- Use proper store subscriptions

## Performance
- Use proper component lazy loading
- Implement proper transitions
- Use proper animations
- Avoid unnecessary reactivity
- Use proper event forwarding
- Implement proper key blocks

## Routing
- Use SvelteKit for routing
- Implement proper layouts
- Use proper route parameters
- Handle loading states properly
- Implement proper error pages
- Use proper navigation methods

## Forms
- Use proper form bindings
- Implement proper validation
- Handle form submission properly
- Show proper loading states
- Use proper error handling
- Implement proper form reset

## TypeScript Integration
- Use proper component types
- Implement proper prop types
- Use proper event types
- Handle proper type inference
- Use proper store types
- Implement proper action types

## Testing
- Write proper unit tests
- Implement proper component tests
- Use proper testing libraries
- Test stores properly
- Implement proper mocking
- Test async operations

## Best Practices
- Follow Svelte style guide
- Use proper naming conventions
- Keep components organized
- Implement proper error handling
- Use proper event handling
- Document complex logic

## Build and Tooling
- Use Vite for development
- Configure proper build setup
- Use proper environment variables
- Implement proper code splitting
- Use proper asset handling
- Configure proper optimization 

## Contents from awesome-cursorrules/rules-new/tailwind.mdc

---
description: Tailwind CSS and UI component best practices for modern web applications
globs: **/*.css, **/*.tsx, **/*.jsx, tailwind.config.js, tailwind.config.ts
---

# Tailwind CSS Best Practices

## Project Setup
- Use proper Tailwind configuration
- Configure theme extension properly
- Set up proper purge configuration
- Use proper plugin integration
- Configure custom spacing and breakpoints
- Set up proper color palette

## Component Styling
- Use utility classes over custom CSS
- Group related utilities with @apply when needed
- Use proper responsive design utilities
- Implement dark mode properly
- Use proper state variants
- Keep component styles consistent

## Layout
- Use Flexbox and Grid utilities effectively
- Implement proper spacing system
- Use container queries when needed
- Implement proper responsive breakpoints
- Use proper padding and margin utilities
- Implement proper alignment utilities

## Typography
- Use proper font size utilities
- Implement proper line height
- Use proper font weight utilities
- Configure custom fonts properly
- Use proper text alignment
- Implement proper text decoration

## Colors
- Use semantic color naming
- Implement proper color contrast
- Use opacity utilities effectively
- Configure custom colors properly
- Use proper gradient utilities
- Implement proper hover states

## Components
- Use shadcn/ui components when available
- Extend components properly
- Keep component variants consistent
- Implement proper animations
- Use proper transition utilities
- Keep accessibility in mind

## Responsive Design
- Use mobile-first approach
- Implement proper breakpoints
- Use container queries effectively
- Handle different screen sizes properly
- Implement proper responsive typography
- Use proper responsive spacing

## Performance
- Use proper purge configuration
- Minimize custom CSS
- Use proper caching strategies
- Implement proper code splitting
- Optimize for production
- Monitor bundle size

## Best Practices
- Follow naming conventions
- Keep styles organized
- Use proper documentation
- Implement proper testing
- Follow accessibility guidelines
- Use proper version control 

## Contents from awesome-cursorrules/rules-new/typescript.mdc

---
description: TypeScript coding standards and best practices for modern web development
globs: **/*.ts, **/*.tsx, **/*.d.ts
---

# TypeScript Best Practices

## Type System
- Prefer interfaces over types for object definitions
- Use type for unions, intersections, and mapped types
- Avoid using `any`, prefer `unknown` for unknown types
- Use strict TypeScript configuration
- Leverage TypeScript's built-in utility types
- Use generics for reusable type patterns

## Naming Conventions
- Use PascalCase for type names and interfaces
- Use camelCase for variables and functions
- Use UPPER_CASE for constants
- Use descriptive names with auxiliary verbs (e.g., isLoading, hasError)
- Prefix interfaces for React props with 'Props' (e.g., ButtonProps)

## Code Organization
- Keep type definitions close to where they're used
- Export types and interfaces from dedicated type files when shared
- Use barrel exports (index.ts) for organizing exports
- Place shared types in a `types` directory
- Co-locate component props with their components

## Functions
- Use explicit return types for public functions
- Use arrow functions for callbacks and methods
- Implement proper error handling with custom error types
- Use function overloads for complex type scenarios
- Prefer async/await over Promises

## Best Practices
- Enable strict mode in tsconfig.json
- Use readonly for immutable properties
- Leverage discriminated unions for type safety
- Use type guards for runtime type checking
- Implement proper null checking
- Avoid type assertions unless necessary

## Error Handling
- Create custom error types for domain-specific errors
- Use Result types for operations that can fail
- Implement proper error boundaries
- Use try-catch blocks with typed catch clauses
- Handle Promise rejections properly

## Patterns
- Use the Builder pattern for complex object creation
- Implement the Repository pattern for data access
- Use the Factory pattern for object creation
- Leverage dependency injection
- Use the Module pattern for encapsulation 


## Contents from awesome-cursorrules/rules/typescript-vuejs-cursorrules-prompt-file/.cursorrules

Code Style and Structure:

Naming Conventions:

TypeScript Usage:

Syntax and Formatting:

Error Handling and Validation:

UI and Styling:

Performance Optimization:

Key Conventions:
Follow Vue.js docs for where makes sense


## Contents from awesome-cursorrules/rules/typescript-vuejs-cursorrules-prompt-file/error-handling-and-validation.mdc
---
description: Rules for handling errors and validating input.
globs: **/*.{js,ts,jsx,tsx,py}
---
- Implement robust error handling using try-catch blocks.
- Validate user input to prevent unexpected errors or security vulnerabilities.
- Log errors and exceptions to facilitate debugging.
- Provide informative error messages to users.

## Contents from awesome-cursorrules/rules/typescript-vuejs-cursorrules-prompt-file/general-code-style-and-structure.mdc
---
description: Applies general code style and structure guidelines to JavaScript, TypeScript, Python files.
globs: **/*.{js,ts,jsx,tsx,py}
---
- Maintain consistent code formatting and indentation.
- Organize code into logical modules and functions.
- Keep functions short and focused on a single task.
- Use comments to explain complex logic or algorithms.

## Contents from awesome-cursorrules/rules/typescript-vuejs-cursorrules-prompt-file/naming-conventions.mdc
---
description: Enforces specific naming conventions across the project.
globs: **/*.{js,ts,jsx,tsx,py}
---
- Use descriptive and meaningful names.
- Follow camelCase for variables and functions (e.g., `myVariable`, `myFunction`).
- Use PascalCase for class names (e.g., `MyClass`).
- Avoid abbreviations unless they are widely understood.

## Contents from awesome-cursorrules/rules/typescript-vuejs-cursorrules-prompt-file/performance-optimization.mdc
---
description: Rules for optimizing application performance.
globs: **/*.{js,ts,jsx,tsx,vue}
---
- Optimize images and other assets for faster loading times.
- Use lazy loading to improve initial page load performance.
- Minimize the number of HTTP requests.
- Avoid unnecessary DOM manipulations.

## Contents from awesome-cursorrules/rules/typescript-vuejs-cursorrules-prompt-file/syntax-and-formatting.mdc
---
description: Defines syntax and formatting rules for consistent code appearance.
globs: **/*.{js,ts,jsx,tsx,py}
---
- Use consistent indentation (e.g., 2 spaces or 4 spaces).
- Keep lines under a reasonable length (e.g., 80-120 characters).
- Use consistent bracing style (e.g., K&R or Allman).
- Avoid unnecessary semicolons where possible.

## Contents from awesome-cursorrules/rules/typescript-vuejs-cursorrules-prompt-file/typescript-usage.mdc
---
description: Specific rules and guidelines for using TypeScript.
globs: **/*.{ts,tsx}
---
- Use explicit types for variables and function parameters.
- Leverage interfaces and type aliases for code reusability and clarity.
- Enable strict mode in `tsconfig.json` to catch potential errors.
- Prefer `const` over `let` when possible to enforce immutability.

## Contents from awesome-cursorrules/rules/typescript-vuejs-cursorrules-prompt-file/ui-and-styling.mdc
---
description: Guidelines for UI and styling in Vue.js components.
globs: src/components/**/*.{vue,scss,css}
---
- Maintain a consistent design language across the application.
- Use CSS preprocessors (e.g., Sass, Less) for improved styling capabilities.
- Follow BEM (Block Element Modifier) naming conventions for CSS classes.

## Contents from awesome-cursorrules/rules/typescript-vuejs-cursorrules-prompt-file/vue-js-conventions.mdc
---
description: Specific conventions for Vue.js components. Follow Vue.js docs where appropriate.
globs: src/components/**/*.vue
---
- Follow Vue.js documentation for best practices.
- Organize component options in a consistent order (e.g., data, computed, methods, watch, lifecycle hooks).
- Use `v-bind` and `v-on` directives for data binding and event handling.
- Prefer using single file components (.vue files).

## Contents from awesome-cursorrules/rules/typescript-react-nextui-supabase-cursorrules-promp/.cursorrules

# Codebase Overview

This codebase appears to be part of a web application built using TypeScript, React, and various NextUI components. It is structured to support a landing page, authentication flows, and a dashboard for logged-in users. The application integrates with Supabase for backend services, including authentication and database interactions.

# Stack and Key Technologies

Frontend Framework: React
TypeScript: Used for type-safe code across the frontend.
NextUI: A React UI library used for building the UI components like buttons, modals, inputs, etc.
Supabase: An open-source Firebase alternative used for backend services like authentication, database, and storage.
Next.js: Likely used as the React framework, indicated by the usage of next/navigation and server utilities.
Iconify: For icons across the application.

Purpose and Functionality

## Authentication

The application includes a comprehensive authentication flow:
Login: Users can log in using email/password or GitHub OAuth. The login logic is handled in frontend/app/(landing-page)/login/action.ts.
Signup: New users can sign up with an email and password. The signup logic is also in frontend/app/(landing-page)/login/action.ts.
Logout: Users can log out, with the logic located in frontend/app/(landing-page)/logout/action.ts.
Email Confirmation: The application handles email confirmation through a callback route in frontend/app/auth/callback/confirm/route.ts.

## User Interface

Landing Page: Contains components like SubmitButton, LoginPage, and LogoutModal to facilitate user interactions.
Dashboard: For logged-in users, showing personalized content and a sidebar for navigation within the dashboard.
Error Handling: A generic error component is used to display errors and provide a retry mechanism.

## Navigation and Layout

Navbar: A responsive navbar for the landing page and possibly other public pages.
Sidebar: A collapsible sidebar for the dashboard, indicating a more complex, multi-page application structure for authenticated users.

## Contents from awesome-cursorrules/rules/typescript-react-nextui-supabase-cursorrules-promp/authentication-flow-rules.mdc
---
description: Specific rules for authentication flows, including login, signup, and logout actions on landing pages.
globs: frontend/app/(landing-page)/**/*action.ts
---
- Implement login functionality using email/password or GitHub OAuth.
- Implement signup functionality for new users with email and password.
- Implement logout functionality to end user sessions.

## Contents from awesome-cursorrules/rules/typescript-react-nextui-supabase-cursorrules-promp/email-confirmation-rule.mdc
---
description: Specific rules for handling email confirmation callbacks in the authentication process.
globs: frontend/app/auth/callback/confirm/route.ts
---
- Handle email confirmation through the callback route.
- Verify and activate user accounts upon successful email confirmation.
- Ensure proper error handling for invalid or expired confirmation links.

## Contents from awesome-cursorrules/rules/typescript-react-nextui-supabase-cursorrules-promp/general-frontend-rule.mdc
---
description: General rules applying to the entire frontend codebase, including TypeScript usage and navigation patterns.
globs: frontend/**/*.{ts,tsx,js,jsx}
---
- Implement responsive navigation using Navbar and Sidebar components.
- Handle errors gracefully using a generic error component.

## Contents from awesome-cursorrules/rules/typescript-react-nextui-supabase-cursorrules-promp/react-ui-components-rule.mdc
---
description: Rules for React UI components using NextUI library. Focuses on UI development patterns for the frontend.
globs: frontend/**/*.{ts,tsx,js,jsx}
---
- Utilize NextUI components (buttons, modals, inputs, etc.) for consistent UI elements.

## Contents from awesome-cursorrules/rules/typescript-react-nextui-supabase-cursorrules-promp/supabase-backend-rule.mdc
---
description: Rules for interacting with Supabase backend services within the frontend, specifically authentication flows.
globs: frontend/**/*action.ts
---
- Manage user sessions and data securely with Supabase SDK.

## Contents from awesome-cursorrules/rules/typescript-react-nextjs-cloudflare-cursorrules-pro/.cursorrules

You are an expert in TypeScript, Node.js, Next.js App Router, React, Shadcn UI, Radix UI, Tailwind CSS and DrizzleORM.
You are also excellent at Cloudflare developer tools like D1 serverless database and KV. You can suggest usage of new tools (changes in wrangler.toml file) to add more primitives like:

R2: File storage
KV: Key-value storage
AI: AI multimodal inference
others primitives in wrangler.toml

In the terminal, you are also an expert at suggesting wrangler commands.

## Contents from awesome-cursorrules/rules/typescript-react-nextjs-cloudflare-cursorrules-pro/cloudflare-developer-tools-rule.mdc
---
description: Focuses on Cloudflare developer tools and suggestions for new primitives in the wrangler.toml file.
globs: **/wrangler.toml
---
- You are also excellent at Cloudflare developer tools like D1 serverless database and KV. You can suggest usage of new tools (changes in wrangler.toml file) to add more primitives like:
  R2: File storage
  KV: Key-value storage
  AI: AI multimodal inference
  others primitives in wrangler.toml

## Contents from awesome-cursorrules/rules/typescript-react-nextjs-cloudflare-cursorrules-pro/general-typescript-node-js-next-js-rule.mdc
---
description: General rules for TypeScript, Node.js and Next.js projects, focusing on best practices and preferred technologies.
globs: **/*.{ts,tsx,js,jsx}
---
- You are an expert in TypeScript, Node.js, Next.js App Router, React, Shadcn UI, Radix UI, Tailwind CSS and DrizzleORM.

## Contents from awesome-cursorrules/rules/typescript-react-nextjs-cloudflare-cursorrules-pro/terminal-commands-rule.mdc
---
description: Specifies expertise in suggesting wrangler commands within the terminal environment.
globs: **/*
---
- In the terminal, you are also an expert at suggesting wrangler commands.

## Contents from awesome-cursorrules/rules/typescript-react-cursorrules-prompt-file/.cursorrules

// TypeScript React .cursorrules

// Prefer functional components

const preferFunctionalComponents = true;

// TypeScript React best practices

const typescriptReactBestPractices = [
  "Use React.FC for functional components with props",
  "Utilize useState and useEffect hooks for state and side effects",
  "Implement proper TypeScript interfaces for props and state",
  "Use React.memo for performance optimization when needed",
  "Implement custom hooks for reusable logic",
  "Utilize TypeScript's strict mode",
];

// Folder structure

const folderStructure = `
src/
  components/
  hooks/
  pages/
  types/
  utils/
  App.tsx
  index.tsx
`;

// Additional instructions

const additionalInstructions = `
1. Use .tsx extension for files with JSX
2. Implement strict TypeScript checks
3. Utilize React.lazy and Suspense for code-splitting
4. Use type inference where possible
5. Implement error boundaries for robust error handling
6. Follow React and TypeScript best practices and naming conventions
7. Use ESLint with TypeScript and React plugins for code quality
`;

## Contents from awesome-cursorrules/rules/typescript-react-cursorrules-prompt-file/typescript-react---additional-instructions.mdc
---
description: Provides additional instructions for TypeScript React development, including file extensions, strict checks, and error handling.
globs: **/*.tsx
---
- Use .tsx extension for files with JSX
- Implement strict TypeScript checks
- Utilize React.lazy and Suspense for code-splitting
- Use type inference where possible
- Follow React and TypeScript best practices and naming conventions
- Use ESLint with TypeScript and React plugins for code quality

## Contents from awesome-cursorrules/rules/typescript-react-cursorrules-prompt-file/typescript-react---best-practices.mdc
---
description: Enforces TypeScript React best practices related to using React.FC, hooks, interfaces, and optimization techniques.
globs: src/**/*.*
---
- Use React.FC for functional components with props
- Utilize useState and useEffect hooks for state and side effects
- Implement proper TypeScript interfaces for props and state
- Use React.memo for performance optimization when needed

## Contents from awesome-cursorrules/rules/typescript-react-cursorrules-prompt-file/typescript-react---folder-structure.mdc
---
description: Defines the preferred folder structure for TypeScript React projects to maintain a consistent organization.
globs: src/**/*.*
---
- Recommended folder structure:
  src/
    components/
    hooks/
    pages/
    types/
    utils/
    App.tsx
    index.tsx

## Contents from awesome-cursorrules/rules/typescript-nodejs-react-vite-cursorrules-prompt-fi/.cursorrules

You are an expert in TypeScript, Node.js, React, Vite, TanStack Query, TanStack Router, and Tailwind.

Response Constraints
- Do not remove any existing code unless necessary.
- Do not remove my comments or commented-out code unless necessary.
- Do not change the formatting of my imports.
- Do not change the formatting of my code unless important for new functionality.

## Contents from awesome-cursorrules/rules/typescript-nodejs-react-vite-cursorrules-prompt-fi/general-typescript-node-js-react-rule.mdc
---
description: Applies general coding guidelines for TypeScript, Node.js, and React projects including response constraints, code style, naming conventions, and UI/styling.
globs: **/*.{ts,tsx,js,jsx}
---
- You are an expert in TypeScript, Node.js, React, Vite, TanStack Query, TanStack Router, and Tailwind.

Response Constraints
- Do not remove any existing code unless necessary.
- Do not remove my comments or commented-out code unless necessary.
- Do not change the formatting of my imports.
- Do not change the formatting of my code unless important for new functionality.

## Contents from awesome-cursorrules/rules/typescript-nodejs-react-vite-cursorrules-prompt-fi/performance-optimization-rule.mdc
---
description: Focuses on performance optimization techniques for TypeScript, React, and Node.js projects.
globs: **/*.{ts,tsx,js,jsx}
---
Performance Optimization
- Look for ways to make things faster:
  - Use immutable data structures
  - Use efficient data fetching strategies
  - Optimize network requests
  - Use efficient data structures
  - Use efficient algorithms
  - Use efficient rendering strategies
  - Use efficient state management

## Contents from awesome-cursorrules/rules/typescript-nodejs-nextjs-react-ui-css-cursorrules-/.cursorrules

- Use 'nuqs' for URL search parameter state management.

Follow Next.js docs for Data Fetching, Rendering, and Routing.

## Contents from awesome-cursorrules/rules/typescript-nodejs-nextjs-react-ui-css-cursorrules-/ui-component-styling-rule.mdc
---
description: Focuses on styling conventions and UI component structure using Shadcn UI, Radix UI, and Tailwind CSS.  It emphasizes responsive design and a mobile-first approach for UI components.
globs: components/**/*.{ts,tsx,js,jsx}
---
- You are an expert in Shadcn UI, Radix UI and Tailwind.

## Contents from awesome-cursorrules/rules/typescript-nodejs-nextjs-app-cursorrules-prompt-fi/.cursorrules

Please write me a web application in this mentioned style for an app with the following features:

please install all necessary npm packages first
at the end the app should fully work and run in dev mode
it will be a notes app
a entry where you can add a new note
a list of all notes
a detail page for each note
a edit page for each note
a delete button for each note
please also add a search field to the list of notes
please also add a filter field to the list of notes
please also add a sort field to the list of notes
please also add a pagination to the list of notes
please also add a loading state to the list of notes
please also add an error state to the list of notes
please add a drag and drop feature to the list of notes

## Contents from awesome-cursorrules/rules/typescript-nodejs-nextjs-ai-cursorrules-prompt-fil/.cursorrules
DO NOT GIVE ME HIGH LEVEL SHIT, IF I ASK FOR FIX OR EXPLANATION, I WANT ACTUAL CODE OR EXPLANATION!!!

! DON'T WANT "Here's how you can blablabla"

If i ask for adjustments to code I have provided you, do not repeat all of my code unnecessarily. Instead try to keep the answer brief by giving just a couple lines before/after any changes you make. Multiple code blocks are ok.

## Contents from awesome-cursorrules/rules/typescript-nodejs-nextjs-ai-cursorrules-prompt-fil/general-project-instructions.mdc
---
description: General instructions for the project, covering code explanation and modifications.
globs: *
---
- DO NOT GIVE ME HIGH LEVEL SHIT, IF I ASK FOR FIX OR EXPLANATION, I WANT ACTUAL CODE OR EXPLANATION!!!
- ! DON'T WANT "Here's how you can blablabla"
- If i ask for adjustments to code I have provided you, do not repeat all of my code unnecessarily. Instead try to keep the answer brief by giving just a couple lines before/after any changes you make. Multiple code blocks are ok.

## Contents from awesome-cursorrules/rules/typescript-nodejs-nextjs-ai-cursorrules-prompt-fil/python-dependency-management.mdc
---
description: Rule to ensure specific dependency management and Python version are used for a service.
globs: /service-1/**/*.*
---
- Always use UV when installing depdendencies
- Always use python 3.12
- Always use classes instead of function

## Contents from awesome-cursorrules/rules/typescript-nextjs-supabase-cursorrules-prompt-file/.cursorrules

You are an expert in TypeScript, Node.js, Next.js App Router, React, Shadcn UI, Radix UI, Supabase, Tailwind, and Vercel AI SDK.

**Vercel AI SDK Integration**

- Use Vercel AI SDK for building AI-powered features.
- Implement AI SDK Core for generating text, structured objects, and tool calls with LLMs.
- Utilize AI SDK UI hooks for building chat interfaces.
- Leverage AI SDK RSC for streaming generative user interfaces with React Server Components.

**Data Fetching and API Routes**

- Implement efficient caching and revalidation strategies using Next.js built-in features.
- Use route handlers (route.ts) for API routes in the App Router.

**Error Handling and Loading States**

- Implement error boundaries and error.tsx files for error handling.
- Use loading.tsx files for managing loading states.

**SEO and Metadata**

- Use Next.js 14's metadata API for SEO optimization.

## Contents from awesome-cursorrules/rules/typescript-nextjs-react-tailwind-supabase-cursorru/.cursorrules

You are an expert in TypeScript, Nose-Js, Next.Js, Agp Rauter, React, Shaden UE, Radix UI, Supabase, and Tastains.

## Contents from awesome-cursorrules/rules/typescript-nextjs-react-tailwind-supabase-cursorru/agp-router-rules.mdc
---
description: Rules for using the Agp Router.
globs: **/agp-router/**/*.*
---
- You are an expert in Agp Router.
- Use the Agp Router to create routes for your application.

## Contents from awesome-cursorrules/rules/typescript-nextjs-react-tailwind-supabase-cursorru/next-js-general-rules.mdc
---
description: Rules specific to Next.js components and pages.
globs: **/pages/**/*.*
---
- Use best practices for Next.js development, including server-side rendering and static site generation where appropriate.

## Contents from awesome-cursorrules/rules/typescript-nextjs-react-tailwind-supabase-cursorru/radix-ui-specific-rules.mdc
---
description: Specific rules for Radix UI components.
globs: **/radix-ui/**/*.*
---
- You are an expert in Radix UI.
- Implement Radix UI components according to their documentation and accessibility guidelines.

## Contents from awesome-cursorrules/rules/typescript-nextjs-react-tailwind-supabase-cursorru/shaden-ue-specific-rules.mdc
---
description: Specific rules for Shaden UE.
globs: **/shaden-ue/**/*.*
---
- You are an expert in Shaden UE.
- Adhere to Shaden UE conventions and best practices.

## Contents from awesome-cursorrules/rules/typescript-nextjs-react-tailwind-supabase-cursorru/supabase-specific-rules.mdc
---
description: Specific rules for Supabase.
globs: **/supabase/**/*.*
---
- Follow best practices for Supabase authentication, data storage, and real-time functionality.

## Contents from awesome-cursorrules/rules/typescript-nextjs-react-tailwind-supabase-cursorru/testing-with-nose-js-and-tastains.mdc
---
description: Rules relating to testing using Nose-Js and Tastains.
globs: **/tests/**/*.*
---
- You are an expert in Nose-Js and Tastains.
- Write comprehensive unit and integration tests using Nose-Js and Tastains.


description: Guides the correct usage of TypeScript features like interfaces, types, and enums within Google Apps Script.
globs: **/*.ts
---
- Use TypeScript for all code; prefer interfaces over types.
- Use enums when appropriate for Google Apps Script constants.
- Implement custom types for Google Apps Script objects and return types.

---
description: General rules for TypeScript, React, and Tailwind projects. This rule applies to all JavaScript/TypeScript files.
globs: **/*.{ts,tsx,js,jsx}
---
You are an expert in TypeScript, Next.js App Router, React, and Tailwind.
---
description: Rules for Next.js 14 App Router projects. This rule applies to all files within the 'app' directory.
globs: app/**/*.*
---
Follow @Next.js 14 App Router docs for Data Fetching, Rendering, and Routing.description: Configures the AI to act as a full-stack developer with expertise in React, TypeScript, PHP, Symfony, and Docker.
globs: **/*.*
---
You are a full stack developer with expert knowledge in React, TypeScript, PHP, Symfony and Docker.

---
description: Focuses on rules and best practices for mobile-first design and responsive typography using tailwind.
globs: **/*.{tsx,jsx}
---
- Always design and implement for mobile screens first, then scale up to larger screens.
- Use Tailwind's responsive prefixes (sm:, md:, lg:, xl:) to adjust layouts for different screen sizes.
- Use Tailwind's text utilities with responsive prefixes to adjust font sizes across different screens.
- Consider using a fluid typography system for seamless scaling.
---
description: General UI/UX design best practices for React components using Tailwind CSS.
globs: **/*.{tsx,jsx}
---
- Always design and implement for mobile screens first, then scale up to larger screens.
- Use Tailwind's responsive prefixes (sm:, md:, lg:, xl:) to adjust layouts for different screen sizes.
- Create a design system with consistent colors, typography, spacing, and component styles.
- Utilize Tailwind's configuration file (tailwind.config.js) to define your custom design tokens.
- Use React.lazy() and Suspense for code-splitting and lazy-loading components.
- Implement virtualization for long lists using libraries like react-window.
- Optimize images and use next/image for automatic image optimization in Next.js.
- Use Tailwind's text utilities with responsive prefixes to adjust font sizes across different screens.
- Consider using a fluid typography system for seamless scaling.
- Ensure proper color contrast ratios using Tailwind's text-* and bg-* classes.
- Use semantic HTML elements and ARIA attributes where necessary.
- Implement keyboard navigation support.
- Make interactive elements (buttons, links) at least 44x44 pixels for easy tapping.
- Implement touch gestures for common actions (swipe, pinch-to-zoom) where appropriate.
- Implement proper error boundaries in React.
- Provide clear feedback for user actions (loading states, success/error messages).
- Use subtle animations to enhance UX (e.g., page transitions, micro-interactions).
- Utilize Tailwind's transition utilities or consider libraries like Framer Motion.
- Use libraries like Formik or react-hook-form for efficient form management.
- Implement proper form validation with clear error messages.
- Implement pull-to-refresh for content updates.
- Use smooth scrolling and momentum scrolling.
- Consider using libraries like react-spring for physics-based animations.
---
description: Best practices for interacting with Firebase services, including security and optimization.
globs: **/firebase/**/*.js
---
- Implement proper security rules in Firebase.
- Use Firebase SDK's offline persistence for better performance and offline support.
- Optimize queries to minimize read/write operations.
