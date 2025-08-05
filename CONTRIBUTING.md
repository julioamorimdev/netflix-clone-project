# 🤝 Contributing to Pipocaflix

Thank you for your interest in contributing to Pipocaflix! This document provides guidelines and information for contributors.

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Development Setup](#development-setup)
- [Pull Request Process](#pull-request-process)
- [Issue Reporting](#issue-reporting)
- [Coding Standards](#coding-standards)
- [Testing](#testing)
- [Documentation](#documentation)

## 📜 Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code.

### Our Standards

- Use welcoming and inclusive language
- Be respectful of differing viewpoints and experiences
- Gracefully accept constructive criticism
- Focus on what is best for the community
- Show empathy towards other community members

## 🚀 How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the issue list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps which reproduce the problem**
- **Provide specific examples to demonstrate the steps**
- **Describe the behavior you observed after following the steps**
- **Explain which behavior you expected to see instead and why**
- **Include details about your configuration and environment**

### Suggesting Enhancements

If you have a suggestion for a new feature or enhancement:

- **Use a clear and descriptive title**
- **Provide a step-by-step description of the suggested enhancement**
- **Provide specific examples to demonstrate the steps**
- **Describe the current behavior and explain which behavior you expected to see instead**

### Pull Requests

- Fork the repo and create your branch from `main`
- If you've added code that should be tested, add tests
- If you've changed APIs, update the documentation
- Ensure the test suite passes
- Make sure your code follows the existing code style
- Issue that pull request!

## 🛠️ Development Setup

### Prerequisites

- PHP 7.4 or higher
- MySQL 5.7 or higher
- Apache/Nginx web server
- Composer
- Git

### Local Development

1. **Fork and clone the repository**
   ```bash
   git clone https://github.com/yourusername/pipocaflix.git
   cd pipocaflix
   ```

2. **Install dependencies**
   ```bash
   composer install
   ```

3. **Set up the database**
   ```bash
   # Create database
   mysql -u root -p -e "CREATE DATABASE pipocaflix_dev;"
   
   # Import schema (if available)
   mysql -u root -p pipocaflix_dev < database/schema.sql
   ```

4. **Configure environment**
   ```bash
   cp env.example .env
   # Edit .env with your local settings
   ```

5. **Start development server**
   ```bash
   php -S localhost:8000
   ```

## 🔄 Pull Request Process

1. **Update the README.md** with details of changes if applicable
2. **Update the CHANGELOG.md** with a note describing your changes
3. **The PR will be merged once you have the sign-off** of at least one other developer
4. **Ensure all tests pass** before submitting

### Pull Request Guidelines

- **Keep it focused**: Each PR should address a single issue or feature
- **Write clear commit messages**: Use conventional commit format
- **Add tests**: Include tests for new functionality
- **Update documentation**: Update relevant documentation
- **Follow the existing code style**: Maintain consistency with the codebase

### Commit Message Format

We use [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

Types:
- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that do not affect the meaning of the code
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to the build process or auxiliary tools

## 🐛 Issue Reporting

### Before Submitting an Issue

- **Search existing issues** to see if the problem has already been reported
- **Check the documentation** to see if the answer is already there
- **Try to reproduce the issue** in a clean environment

### Issue Template

When creating an issue, please use the following template:

```markdown
## Bug Report

### Environment
- OS: [e.g., Windows 10, macOS 11.0, Ubuntu 20.04]
- PHP Version: [e.g., 7.4.21]
- MySQL Version: [e.g., 8.0.26]
- Browser: [e.g., Chrome 91, Firefox 89]

### Description
[Describe the bug in detail]

### Steps to Reproduce
1. [First step]
2. [Second step]
3. [And so on...]

### Expected Behavior
[What you expected to happen]

### Actual Behavior
[What actually happened]

### Additional Information
[Any other context about the problem]
```

## 📝 Coding Standards

### PHP Standards

- Follow [PSR-12](https://www.php-fig.org/psr/psr-12/) coding standards
- Use meaningful variable and function names
- Add comments for complex logic
- Keep functions small and focused
- Use type hints where possible

### JavaScript Standards

- Follow [ESLint](https://eslint.org/) rules
- Use meaningful variable and function names
- Add JSDoc comments for functions
- Use modern JavaScript features (ES6+)

### CSS Standards

- Follow [BEM](http://getbem.com/) methodology
- Use meaningful class names
- Keep styles organized and commented
- Use CSS variables for consistent theming

### Database Standards

- Use meaningful table and column names
- Add proper indexes for performance
- Use foreign keys for data integrity
- Document complex queries

## 🧪 Testing

### Running Tests

```bash
# Run all tests
php test/test_suite.php

# Run specific test file
php test/test_specific.php
```

### Writing Tests

- Write tests for all new functionality
- Ensure tests are independent and repeatable
- Use descriptive test names
- Test both success and failure cases

### Test Coverage

- Aim for at least 80% code coverage
- Focus on critical business logic
- Test edge cases and error conditions

## 📚 Documentation

### Code Documentation

- Add PHPDoc comments for all functions and classes
- Include parameter types and return types
- Provide usage examples for complex functions
- Keep documentation up to date with code changes

### API Documentation

- Document all API endpoints
- Include request/response examples
- Specify authentication requirements
- Update documentation when APIs change

## 🏷️ Labels

We use the following labels to categorize issues and pull requests:

- `bug`: Something isn't working
- `enhancement`: New feature or request
- `documentation`: Improvements or additions to documentation
- `good first issue`: Good for newcomers
- `help wanted`: Extra attention is needed
- `question`: Further information is requested
- `wontfix`: This will not be worked on

## 📞 Getting Help

If you need help with contributing:

- **Check the documentation** in the `docs/` folder
- **Search existing issues** for similar problems
- **Create a new issue** with the `question` label
- **Join our community** discussions

## 🙏 Recognition

Contributors will be recognized in:

- The project README
- Release notes
- Contributor hall of fame

## 📄 License

By contributing to Pipocaflix, you agree that your contributions will be licensed under the MIT License.

---

**Thank you for contributing to Pipocaflix! 🎉** 