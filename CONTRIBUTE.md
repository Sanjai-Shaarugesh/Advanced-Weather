# Contributing to Advanced Weather GNOME Extension

Thank you for your interest in contributing to Advanced Weather! This document provides guidelines and information for contributors.

## Code of Conduct

By participating in this project, you agree to maintain a respectful and inclusive environment for all contributors.

## Getting Started

1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Advanced-Weather
   cd Advanced-Weather
   ```
3. Create a new branch for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## Development Setup

1. Ensure you have GNOME Shell 45+ installed
2. Install development dependencies:
   ```bash
   make install-dev
   ```
3. Enable extension development mode:
   ```bash
   gnome-extensions prefs advanced-weather@sanjai-shaarugesh
   ```

## Coding Standards

- Follow existing code style and formatting
- Use meaningful variable and function names
- Comment complex logic
- Keep functions focused and modular
- Use TypeScript for new features when possible

## Testing

1. Run the test suite:
   ```bash
   make test
   ```
2. Test your changes across different GNOME Shell versions
3. Verify functionality with different weather providers
4. Check performance impact of changes

## Pull Request Process

1. Update documentation for any new features
2. Add relevant tests
3. Ensure all tests pass
4. Update the changelog
5. Create a pull request with:
   - Clear title and description
   - Reference to related issues
   - Screenshots/GIFs for UI changes
   - List of tested GNOME Shell versions

## Bug Reports

When submitting bug reports, please include:

1. GNOME Shell version
2. Extension version
3. Steps to reproduce
4. Expected vs actual behavior
5. Screenshots if applicable
6. Weather provider being used
7. System information:
   - Distribution
   - Desktop environment version
   - Relevant logs

## Feature Requests

Feature requests are welcome! Please provide:

1. Clear description of the feature
2. Use cases and benefits
3. Potential implementation approach
4. Mock-ups for UI changes (if applicable)

## Documentation

- Update README.md for user-facing changes
- Update inline documentation for API changes
- Add JSDoc comments for new functions
- Update the wiki if necessary

## Working with Weather APIs

When implementing or modifying weather provider support:

1. Follow API best practices
2. Implement rate limiting
3. Handle errors gracefully
4. Add appropriate documentation
5. Include example API responses

## Localization

- Use translation strings for all user-visible text
- Test with RTL languages
- Update translation templates

## Release Process

1. Update version number
2. Update changelog
3. Create release notes
4. Tag release
5. Submit to GNOME Extensions website

## Getting Help

- Join our community chat
- Check existing issues and discussions
- Review documentation
- Contact maintainers

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

## Resources

- [GNOME Shell Extension Guide](https://gjs.guide/extensions/)
- [GJS Documentation](https://gjs-docs.gnome.org/)
- [GNOME Developer Center](https://developer.gnome.org/)

Thank you for contributing to Advanced Weather!
