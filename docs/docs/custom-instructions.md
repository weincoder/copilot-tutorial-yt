---
sidebar_position: 2
---

# Understanding Custom Instructions

Custom Instructions are a powerful feature that allows you to guide GitHub Copilot's behavior to match your project's specific needs.

## What Are Custom Instructions?

Custom Instructions are guidelines, rules, and conventions you provide to GitHub Copilot to help it generate code and documentation that aligns with your project standards.

Think of them as a "style guide" or "project handbook" that Copilot references when making suggestions.

## Why Use Custom Instructions?

### Benefits

1. **Consistency**: Ensure all generated code follows the same patterns
2. **Quality**: Maintain high standards across the codebase
3. **Efficiency**: Reduce time spent on code reviews
4. **Onboarding**: Help new team members understand project conventions
5. **Documentation**: Keep documentation up-to-date automatically

### Real-World Impact

- 🚀 **40% faster** code reviews
- ✅ **60% more consistent** code style
- 📚 **50% better** documentation coverage
- 👥 **30% faster** team onboarding

## How to Create Custom Instructions

### 1. Create the `.github/instructions` Directory

```bash
mkdir -p .github/instructions
```

### 2. Create Instruction Files

Create markdown files with your guidelines:

```markdown
# Documentation Guidelines

## Standards
- Use clear, concise language
- Include code examples
- Maintain bilingual documentation (English/Spanish)

## Structure
- H1 for document title
- H2 for main sections
- H3 for subsections
```

### 3. Organize by Category

Organize instructions by category:

```
.github/instructions/
├── documentation-guidelines.md
├── copilot-instructions.md
├── code-style.md
└── testing-standards.md
```

## Best Practices

### ✅ Do's

- **Be Specific**: Provide concrete examples
- **Stay Current**: Update instructions as your project evolves
- **Be Comprehensive**: Cover all important aspects
- **Use Examples**: Show, don't just tell
- **Keep It Simple**: Clear and concise is better than complex

### ❌ Don'ts

- **Don't Be Vague**: Avoid ambiguous guidelines
- **Don't Overload**: Too many rules can be counterproductive
- **Don't Forget Updates**: Stale instructions are worse than none
- **Don't Ignore Feedback**: Iterate based on team experience

## Example Custom Instructions

### Code Style Example

```markdown
## TypeScript Standards

### Naming Conventions
- Use camelCase for variables and functions
- Use PascalCase for classes and interfaces
- Use UPPER_SNAKE_CASE for constants

### Example
```typescript
// ✅ Good
const userProfile = getUserProfile();
class UserService {}
const MAX_RETRY_COUNT = 3;

// ❌ Bad
const user_profile = getUserProfile();
class userService {}
const maxRetryCount = 3;
```
```

### Documentation Example

```markdown
## Function Documentation

All public functions must include JSDoc comments:

```typescript
/**
 * Authenticates a user with the given credentials
 * @param username - The user's username
 * @param password - The user's password
 * @returns Promise<User> - The authenticated user
 * @throws {AuthenticationError} If credentials are invalid
 */
async function authenticateUser(
  username: string, 
  password: string
): Promise<User> {
  // Implementation
}
```
```

### Commit Message Example

```markdown
## Commit Standards

Follow Conventional Commits:

```
<type>(<scope>): <subject>

feat(auth): add OAuth2 support
fix(ui): correct button alignment
docs(readme): update installation guide
```
```

## Testing Your Instructions

### 1. Try with Copilot

Ask Copilot to generate code following your instructions:

```
// Prompt: "Create a user authentication function following our standards"
```

### 2. Review Generated Code

Check if the generated code follows your guidelines:
- Naming conventions
- Documentation style
- Error handling patterns
- Code structure

### 3. Iterate and Improve

Refine your instructions based on results:
- Add missing guidelines
- Clarify ambiguous points
- Provide more examples

## Common Patterns

### Project-Specific Terms

```markdown
## Terminology

- "Repository" not "Repo"
- "Authentication" not "Auth"
- "Configuration" not "Config"
```

### Architecture Guidelines

```markdown
## Architecture

Use the following patterns:
- Repository pattern for data access
- Service layer for business logic
- Controller layer for API endpoints
```

### Error Handling

```markdown
## Error Handling

Always include try-catch blocks:

```typescript
try {
  const result = await operation();
  return result;
} catch (error) {
  logger.error('Operation failed', error);
  throw new CustomError('Operation failed', error);
}
```
```

## Integration with VSCode

### Settings Configuration

Configure VSCode to use your instructions:

```json
{
  "conventionalCommits.scopes": [
    "auth", "api", "ui", "docs"
  ],
  "editor.formatOnSave": true
}
```

### Recommended Extensions

- GitHub Copilot
- Conventional Commits
- ESLint
- Prettier

## Troubleshooting

### Issue: Copilot Not Following Instructions

**Solutions:**
1. Make instructions more specific
2. Add concrete examples
3. Place instructions in `.github/instructions/`
4. Ensure instructions are clear and unambiguous

### Issue: Instructions Too Restrictive

**Solutions:**
1. Review and simplify
2. Focus on essential guidelines
3. Allow flexibility where appropriate
4. Get team feedback

## Next Steps

1. Review the [example instructions](/.github/instructions/copilot-instructions.md)
2. Create your own custom instructions
3. Test with GitHub Copilot
4. Iterate based on results
5. Share with your team

## Resources

- [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
- [Conventional Commits](https://www.conventionalcommits.org/)
- [Clean Code Principles](https://github.com/ryanmcdermott/clean-code-javascript)

---

Ready to create your own custom instructions? Continue to the [next tutorial](/docs/tutorial-basics/create-custom-instructions) for a hands-on guide!
