# Contributing to Hello World

Thank you for your interest in contributing to this learning project! This document provides guidelines and instructions for contributing.

## Code of Conduct

Please be respectful and constructive in all interactions with other contributors.

## Getting Started

### Prerequisites
- Git installed on your machine
- GitHub account
- Basic knowledge of Git commands

### Fork and Clone

1. **Fork the repository** by clicking the "Fork" button on GitHub
2. **Clone your fork locally:**
   ```bash
   git clone https://github.com/YOUR-USERNAME/hello-world.git
   cd hello-world
   ```

3. **Add upstream remote:**
   ```bash
   git remote add upstream https://github.com/gasukwo52-commits/hello-world.git
   ```

## Making Changes

### Branch Naming Convention

Use descriptive branch names following this pattern:
- `feature/description` - For new features
- `bugfix/description` - For bug fixes
- `docs/description` - For documentation
- `refactor/description` - For code refactoring

Example:
```bash
git checkout -b feature/add-login-validation
```

### Commit Messages

Write clear, descriptive commit messages:

**Good:**
```
Add email validation to login form
- Validates email format before submission
- Shows error message for invalid emails
- Closes #15
```

**Bad:**
```
fix stuff
update code
```

### Guidelines for Commits
- Keep commits small and focused on a single change
- Use imperative mood: "Add feature" not "Added feature"
- Reference issues when applicable: "Fixes #123"

## Submitting Changes

### Before Creating a Pull Request

1. **Update your branch with latest changes:**
   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

2. **Test your changes** thoroughly

3. **Review your own code** before submitting

### Creating a Pull Request

1. **Push your branch to your fork:**
   ```bash
   git push origin feature/your-feature
   ```

2. **Go to the original repository** and click "New Pull Request"

3. **Fill out the PR template with:**
   - Clear title describing the change
   - Description of what and why you changed it
   - Reference to related issues (if any)
   - Screenshots or examples (if applicable)

### PR Template

```markdown
## Description
Brief description of the changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Code refactoring

## Related Issues
Fixes #(issue number)

## How to Test
Steps to verify the changes work correctly

## Screenshots (if applicable)
Add screenshots showing the changes
```

## Code Style

### General Guidelines
- Use consistent indentation (2 or 4 spaces)
- Use meaningful variable and function names
- Add comments for complex logic
- Keep functions small and focused

### JavaScript/HTML/CSS
- Use single quotes for strings
- Use lowercase for HTML tags and attributes
- Keep CSS classes descriptive and hyphenated
- Avoid inline styles when possible

## Review Process

1. **Maintainer Review** - Your PR will be reviewed by project maintainers
2. **Address Feedback** - Make requested changes and push updates
3. **Approval** - Once approved, your PR will be merged

## Common Contribution Types

### Bug Reports
When reporting bugs, include:
- Description of the bug
- Steps to reproduce
- Expected behavior
- Actual behavior
- Screenshots if applicable

### Feature Requests
When suggesting features:
- Clear description of the feature
- Why it would be useful
- Possible implementation approach
- Example use cases

### Documentation
Help improve documentation by:
- Fixing typos
- Adding examples
- Clarifying instructions
- Translating content

## Questions?

Feel free to:
- Open an issue with your question
- Use GitHub Discussions
- Ask in your PR comments

## Recognition

Contributors will be recognized in:
- The project README
- Commit history
- Release notes

Thank you for contributing! 🎉

---

**Happy Contributing!**
