# Documentation Guidelines

## Purpose
These guidelines ensure consistent, high-quality documentation across the project.

## Documentation Standards

### 1. Structure
- **Clear Hierarchy**: Use proper heading levels (H1 for titles, H2 for sections, etc.)
- **Logical Flow**: Organize content from general to specific
- **Table of Contents**: Include for documents longer than 3 sections

### 2. Writing Style
- **Clarity**: Write in clear, concise language
- **Active Voice**: Prefer active voice over passive
- **Present Tense**: Use present tense when describing features
- **Consistency**: Maintain consistent terminology throughout

### 3. Code Examples
- **Complete**: Provide runnable, complete examples
- **Commented**: Include inline comments for complex logic
- **Formatted**: Use proper syntax highlighting
- **Context**: Explain what the code does before showing it

### 4. Markdown Conventions
```markdown
# H1 - Document Title
## H2 - Main Sections
### H3 - Subsections

**Bold** for emphasis
*Italic* for terms
`code` for inline code
```code blocks``` for multi-line code
> Blockquotes for important notes
```

### 5. Language Requirements
- **English**: Primary documentation language
- **Spanish**: Secondary language for accessibility
- **Bilingual**: Maintain parallel documentation when possible

### 6. Visual Elements
- **Screenshots**: Use screenshots to illustrate UI features
- **Diagrams**: Include diagrams for complex concepts
- **Alt Text**: Always provide alt text for images

### 7. Links and References
- **Internal Links**: Use relative paths for internal links
- **External Links**: Verify all external links are valid
- **References**: Cite sources and provide attributions

### 8. Versioning
- **Version Tags**: Document which version features were added
- **Changelog**: Keep a changelog for documentation updates
- **Deprecation**: Clearly mark deprecated features

## File Organization
```
docs/
├── getting-started/
│   ├── installation.md
│   └── quick-start.md
├── guides/
│   ├── basic/
│   └── advanced/
├── api/
│   └── reference.md
└── contributing/
    └── guidelines.md
```

## Review Checklist
Before submitting documentation:
- [ ] Content is accurate and up-to-date
- [ ] All code examples work
- [ ] Links are valid
- [ ] Spelling and grammar checked
- [ ] Screenshots are current
- [ ] Follows style guide
- [ ] Available in required languages

## Resources
- [Docusaurus Documentation](https://docusaurus.io/)
- [Markdown Guide](https://www.markdownguide.org/)
- [Write the Docs](https://www.writethedocs.org/)
