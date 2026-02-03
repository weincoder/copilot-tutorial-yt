# Custom Instructions for GitHub Copilot

## Overview
These instructions guide GitHub Copilot to produce code and documentation that aligns with our project standards.

## General Principles

### Code Quality
- Write clean, maintainable, and self-documenting code
- Follow established design patterns
- Prioritize readability over cleverness
- Keep functions small and focused on a single responsibility

### Documentation
- Every feature must have corresponding documentation
- Follow the documentation guidelines in `documentation-guidelines.md`
- Update documentation when code changes
- Include both English and Spanish versions when possible

### Testing
- Write tests for all new features
- Maintain test coverage above 80%
- Use descriptive test names
- Follow AAA pattern (Arrange, Act, Assert)

## Language-Specific Guidelines

### TypeScript/JavaScript
```typescript
// Use descriptive variable names
const userAuthentication = new AuthService();

// Document complex functions
/**
 * Authenticates a user with the given credentials
 * @param username - The user's username
 * @param password - The user's password
 * @returns Promise<User> - The authenticated user object
 */
async function authenticateUser(username: string, password: string): Promise<User> {
  // Implementation
}

// Use modern ES6+ features
const { name, email } = user;
const users = [...oldUsers, newUser];
```

### Markdown
- Use clear headings hierarchy
- Include code examples with syntax highlighting
- Add tables for structured data
- Use blockquotes for important notes

## Commit Message Standards
Follow Conventional Commits specification:

```
<type>(<scope>): <subject>

<body>

<footer>
```

### Types
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

### Examples
```
feat(auth): add OAuth2 authentication support

Implemented OAuth2 flow with Google and GitHub providers.
Added user session management with JWT tokens.

Closes #123
```

```
docs(readme): add Spanish translation

Added complete Spanish translation of README.md
Maintained parallel structure with English version.
```

## AI Assistant Guidelines

When GitHub Copilot generates code or documentation:

1. **Follow Project Structure**: Respect existing folder organization
2. **Match Coding Style**: Maintain consistency with existing code
3. **Include Comments**: Add helpful comments for complex logic
4. **Error Handling**: Always include proper error handling
5. **Type Safety**: Use TypeScript types properly
6. **Accessibility**: Consider accessibility in all UI components
7. **Internationalization**: Support multiple languages where applicable
8. **Security**: Follow security best practices
9. **Performance**: Consider performance implications
10. **Documentation**: Update relevant documentation

## Code Review Standards

Code must pass these checks:
- [ ] Follows project coding standards
- [ ] Includes appropriate tests
- [ ] Documentation is updated
- [ ] No security vulnerabilities
- [ ] Passes all CI/CD checks
- [ ] Reviewed by at least one team member

## Resources
- [Conventional Commits](https://www.conventionalcommits.org/)
- [TypeScript Guidelines](https://www.typescriptlang.org/docs/handbook/declaration-files/do-s-and-don-ts.html)
- [Clean Code Principles](https://github.com/ryanmcdermott/clean-code-javascript)
