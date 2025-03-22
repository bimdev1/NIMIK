# Contributing to NIMIK

Thank you for your interest in contributing to NIMIK. This document provides guidelines and instructions for contributing.

## Development Setup

### Prerequisites

- Python 3.9 or higher
- Poetry for dependency management
- Git
- Pre-commit hooks

### Initial Setup

1. Fork and clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/NIMIK.git
   cd NIMIK
   ```

2. Set up your development environment:
   ```bash
   # Install Poetry if you haven't already
   curl -sSL https://install.python-poetry.org | python3 -

   # Install dependencies
   poetry install

   # Install pre-commit hooks
   poetry run pre-commit install
   ```

3. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## Project Structure

```
nimik/
├── .github/                    # GitHub specific files
│   ├── ISSUE_TEMPLATE/        # Issue templates
│   ├── workflows/             # GitHub Actions
│   ├── pull_request_template.md
│   └── SECURITY.md
├── docs/                      # Documentation
│   ├── technical/            # Technical documentation
│   ├── community/            # Community guidelines
│   └── governance/           # Governance documentation
├── src/                      # Source code
│   ├── api/                  # API implementation
│   ├── web/                  # Web interface
│   ├── cli/                  # Command-line tools
│   └── core/                 # Core functionality
├── tests/                    # Test suite
│   ├── unit/
│   ├── integration/
│   └── cultural/             # Cultural safety tests
├── scripts/                  # Utility scripts
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md           # This file
├── LICENSE
├── PHILOSOPHY.md
└── README.md
```

## Cultural and Ethical Guidelines

1. **Indigenous Data Sovereignty**
   - All contributions must respect Indigenous data sovereignty principles
   - Follow established cultural protocols
   - Protect community privacy and security

2. **Trauma-Informed Development**
   - Use trauma-informed language and approaches
   - Consider emotional impact of features
   - Implement appropriate content warnings

3. **Accessibility**
   - Follow WCAG 2.1 Level AA standards
   - Test with screen readers
   - Provide alternative text for images

## Technical Guidelines

1. **Code Style and Quality**
   - Code is automatically formatted with Black
   - Imports are sorted with isort
   - Type checking with mypy
   - Linting with ruff
   - Pre-commit hooks enforce these standards

2. **Testing**
   - Write unit tests for new features
   - Include integration tests
   - Add cultural safety tests
   - Run tests with pytest:
     ```bash
     poetry run pytest
     ```

3. **Documentation**
   - Update relevant documentation
   - Follow documentation style guide
   - Include context and rationale
   - Document any new dependencies

## Quality Checks

Our pre-commit hooks enforce several checks:

1. **Code Quality**
   - Trailing whitespace removal
   - End-of-file fixes
   - YAML validation
   - Black formatting
   - isort import sorting
   - Ruff linting
   - mypy type checking

2. **Cultural Safety**
   - Language sensitivity
   - Cultural appropriateness
   - Trauma-informed content
   - Accessibility standards

3. **Security**
   - Secret detection
   - Dependency scanning
   - Basic security checks

To run checks manually:
```bash
poetry run pre-commit run --all-files
```

## Contribution Process

1. **Before Starting**
   - Check existing issues and discussions
   - Read relevant documentation
   - Consult community guidelines

2. **Making Changes**
   - Create a feature branch
   - Make focused commits
   - Follow coding standards
   - Run quality checks

3. **Submitting Changes**
   - Update documentation
   - Run all tests
   - Create a pull request using our template
   - Respond to feedback

4. **Review Process**
   - Technical review
   - Cultural safety review
   - Community consultation
   - Final approval

## Getting Help

- Open a [Discussion](https://github.com/bimdev1/NIMIK/discussions) for questions
- Check our [Documentation](./docs/)
- Review [Security Policy](/.github/SECURITY.md)
- Join community calls (schedule in docs)

## Recognition

We recognize all types of contributions:
- Code
- Documentation
- Design
- Community building
- Cultural guidance
- Testing and feedback

## Code of Conduct

All contributors must follow our [Code of Conduct](CODE_OF_CONDUCT.md).
