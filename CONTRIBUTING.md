# Contributing to Eremos

Thank you for your interest in contributing to Eremos! This document provides guidelines and information for contributors.

## 🚀 Quick Start

1. **Fork** the repository
2. **Clone** your fork: `git clone https://github.com/YOUR_USERNAME/Eremos.git`
3. **Install** dependencies: `npm install`
4. **Create** a feature branch: `git checkout -b feature/amazing-feature`
5. **Make** your changes
6. **Test** your changes: `npm test`
7. **Commit** your changes: `git commit -m 'Add amazing feature'`
8. **Push** to your branch: `git push origin feature/amazing-feature`
9. **Open** a Pull Request

## 🛠️ Development Setup

### Prerequisites
- Node.js 18+ 
- npm 8+
- Git

### Installation
```bash
git clone https://github.com/EremosCore/Eremos.git
cd Eremos
npm install
```

### Available Scripts
```bash
npm run dev          # Start development mode
npm run build        # Build the project
npm test             # Run tests
npm run lint         # Lint code
npm run format       # Format code
npm run clean        # Clean build artifacts
```

## 📝 Code Style

### TypeScript
- Use TypeScript for all new code
- Follow strict type checking
- Use interfaces for object shapes
- Prefer `const` over `let`
- Use meaningful variable names

### Formatting
- Use Prettier for code formatting
- Run `npm run format` before committing
- Use 2 spaces for indentation
- Use single quotes for strings
- Use semicolons

### Linting
- Follow ESLint rules
- Run `npm run lint` before committing
- Fix any linting errors

## 🧪 Testing

### Writing Tests
- Write tests for all new functionality
- Use Jest as the testing framework
- Place tests in the `tests/` directory
- Use descriptive test names
- Test both success and error cases

### Running Tests
```bash
npm test              # Run all tests
npm run test:watch    # Run tests in watch mode
npm run test:coverage # Run tests with coverage
```

## 🏗️ Architecture Guidelines

### Agent Development
- Follow the agent interface in `types/agent.ts`
- Implement required methods: `observe()`, `getMemory()`
- Use descriptive names and clear logic
- Keep agents focused on single responsibilities
- Use the shared utilities in `utils/`

### Signal Generation
- Use `generateSignalHash()` for all outputs
- Follow the signal structure in `types/signal.ts`
- Include confidence scores (0-1)
- Use appropriate glyphs for visual identification

### Memory Management
- Implement efficient memory storage
- Use the memory interface in `types/agent.ts`
- Clean up old data appropriately
- Consider memory limits for long-running agents

## 📚 Documentation

### Code Documentation
- Use JSDoc comments for public APIs
- Include examples in documentation
- Update README.md for user-facing changes
- Document any new configuration options

### Agent Documentation
- Document agent purpose and behavior
- Include configuration examples
- Document signal types and confidence factors
- Provide usage examples

## 🔄 Pull Request Process

### Before Submitting
1. Ensure all tests pass
2. Run linting and formatting
3. Update documentation if needed
4. Test your changes thoroughly

### PR Description
- Describe the problem you're solving
- Explain your solution approach
- Include any relevant issue numbers
- Add screenshots for UI changes
- List any breaking changes

### Review Process
- All PRs require at least one review
- Address review comments promptly
- Keep PRs focused and manageable
- Squash commits before merging

## 🐛 Bug Reports

### Reporting Bugs
- Use the GitHub issue template
- Include steps to reproduce
- Provide error messages and logs
- Include system information
- Describe expected vs actual behavior

### Bug Fixes
- Reference the issue number in your PR
- Include tests that prevent regression
- Test the fix thoroughly
- Update documentation if needed

## ✨ Feature Requests

### Suggesting Features
- Use the GitHub issue template
- Explain the problem you're solving
- Describe your proposed solution
- Consider implementation complexity
- Discuss with maintainers first

### Implementing Features
- Get approval before starting work
- Break large features into smaller PRs
- Include comprehensive tests
- Update documentation
- Consider backward compatibility

## 🤝 Community Guidelines

### Communication
- Be respectful and inclusive
- Use clear and constructive language
- Ask questions when unsure
- Help other contributors

### Code of Conduct
- Follow the project's code of conduct
- Report inappropriate behavior
- Maintain a welcoming environment
- Focus on technical merit

## 📞 Getting Help

### Resources
- [Agent Guide](docs/agents.md)
- [Architecture Documentation](docs/architecture.md)
- [API Reference](docs/api.md)
- [Discord Community](https://discord.gg/eremos)

### Questions
- Open a GitHub issue for questions
- Join our Discord community
- Check existing documentation
- Review previous issues and PRs

## 🎯 Contribution Areas

### High Priority
- Bug fixes and stability improvements
- Performance optimizations
- Test coverage improvements
- Documentation updates

### Medium Priority
- New agent implementations
- Utility function additions
- Configuration improvements
- Monitoring and logging

### Low Priority
- UI/UX improvements
- Additional examples
- Code style improvements
- Minor optimizations

## 🏆 Recognition

Contributors are recognized in several ways:
- GitHub contributor status
- Mention in release notes
- Recognition in documentation
- Community appreciation

Thank you for contributing to Eremos! 🚀
