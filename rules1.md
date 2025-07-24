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

---

# Vue.js Best Practices

## Component Structure
- Use Composition API over Options API
- Keep components small and focused
- Use proper TypeScript integration
- Implement proper props validation
- Use proper emit declarations
- Keep template logic minimal

## Composition API
- Use proper ref and reactive
- Implement proper lifecycle hooks
- Use composables for reusable logic
- Keep setup function clean
- Use proper computed properties
- Implement proper watchers

## State Management
- Use Pinia for state management
- Keep stores modular
- Use proper state composition
- Implement proper actions
- Use proper getters
- Handle async state properly

## Performance
- Use proper component lazy loading
- Implement proper caching
- Use proper computed properties
- Avoid unnecessary watchers
- Use proper v-show vs v-if
- Implement proper key management

## Routing
- Use Vue Router properly
- Implement proper navigation guards
- Use proper route meta fields
- Handle route params properly
- Implement proper lazy loading
- Use proper navigation methods

## Forms
- Use v-model properly
- Implement proper validation
- Handle form submission properly
- Show proper loading states
- Use proper error handling
- Implement proper form reset

## TypeScript Integration
- Use proper component type definitions
- Implement proper prop types
- Use proper emit declarations
- Handle proper type inference
- Use proper composable types
- Implement proper store types

## Testing
- Write proper unit tests
- Implement proper component tests
- Use Vue Test Utils properly
- Test composables properly
- Implement proper mocking
- Test async operations

## Best Practices
- Follow Vue style guide
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
- Use proper test fixtures
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

---

# Python Best Practices

## Project Structure
- Use src-layout with `src/your_package_name/`
- Place tests in `tests/` directory parallel to `src/`
- Keep configuration in `config/` or as environment variables
- Store requirements in `requirements.txt` or `pyproject.toml`
- Place static files in `static/` directory
- Use `templates/` for Jinja2 templates

## Code Style
- Follow Black code formatting
- Use isort for import sorting
- Follow PEP 8 naming conventions:
  - snake_case for functions and variables
  - PascalCase for classes
  - UPPER_CASE for constants
- Maximum line length of 88 characters (Black default)
- Use absolute imports over relative imports

## Type Hints
- Use type hints for all function parameters and returns
- Import types from `typing` module
- Use `Optional[Type]` instead of `Type | None`
- Use `TypeVar` for generic types
- Define custom types in `types.py`
- Use `Protocol` for duck typing

## Flask Structure
- Use Flask factory pattern
- Organize routes using Blueprints
- Use Flask-SQLAlchemy for database
- Implement proper error handlers
- Use Flask-Login for authentication
- Structure views with proper separation of concerns

## Database
- Use SQLAlchemy ORM
- Implement database migrations with Alembic
- Use proper connection pooling
- Define models in separate modules
- Implement proper relationships
- Use proper indexing strategies

## Authentication
- Use Flask-Login for session management
- Implement Google OAuth using Flask-OAuth
- Hash passwords with bcrypt
- Use proper session security
- Implement CSRF protection
- Use proper role-based access control

## API Design
- Use Flask-RESTful for REST APIs
- Implement proper request validation
- Use proper HTTP status codes
- Handle errors consistently
- Use proper response formats
- Implement proper rate limiting

## Testing
- Use pytest for testing
- Write tests for all routes
- Use pytest-cov for coverage
- Implement proper fixtures
- Use proper mocking with pytest-mock
- Test all error scenarios

## Security
- Use HTTPS in production
- Implement proper CORS
- Sanitize all user inputs
- Use proper session configuration
- Implement proper logging
- Follow OWASP guidelines

## Performance
- Use proper caching with Flask-Caching
- Implement database query optimization
- Use proper connection pooling
- Implement proper pagination
- Use background tasks for heavy operations
- Monitor application performance

## Error Handling
- Create custom exception classes
- Use proper try-except blocks
- Implement proper logging
- Return proper error responses
- Handle edge cases properly
- Use proper error messages

## Documentation
- Use Google-style docstrings
- Document all public APIs
- Keep README.md updated
- Use proper inline comments
- Generate API documentation
- Document environment setup

## Development Workflow
- Use virtual environments (venv)
- Implement pre-commit hooks
- Use proper Git workflow
- Follow semantic versioning
- Use proper CI/CD practices
- Implement proper logging

## Dependencies
- Pin dependency versions
- Use requirements.txt for production
- Separate dev dependencies
- Use proper package versions
- Regularly update dependencies
- Check for security vulnerabilities