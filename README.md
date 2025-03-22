# NIMIK (National Index of Missing Indigenous Kin)

**NIMIK** is an open-source, trauma-informed archive preserving public data on Missing and Murdered Indigenous People (MMIP) across North America. It is built in collaboration with kinship, sovereignty, and survivorship—not extraction or institutional erasure.

This project exists to restore **visibility**, **accountability**, and **community ownership** to cases that have long been ignored, mishandled, or actively concealed.

---

## Project Scope

NIMIK is not just a database—it is a modular, community-driven system designed to:

- Aggregate and verify public MMIP data
- Provide a searchable, accessible, and trauma-informed public interface
- Offer tools for kin, journalists, advocates, and tribal orgs to access and use case data
- Model ethical, decolonial approaches to open-source software development

The system includes:

- **CLI Tool** for terminal-based search and ingestion
- **Public UI** for accessible, trauma-informed exploration
- **Read-only API** for programmatic access
- **Documentation Suite** covering everything from values to technical pipeline

---

## Who This Is For

NIMIK serves multiple audiences:

- **Families & Kin** seeking visibility and justice
- **Journalists & Researchers** accessing verified public data
- **Advocates & Community Organizers** tracking patterns and state neglect
- **Developers** supporting trauma-informed, anti-carceral systems
- **Educators & Historians** working on MMIP accountability

---

## Ethics & Philosophy

NIMIK is built on **non-extractive**, **trauma-informed**, and **anti-carceral** principles.
We do not "collect" cases—we preserve them.
We do not centralize data for control—we build decentralized accountability.

We believe:

- Public data is not neutral
- Families deserve agency over their stories
- Tools must be built with—not just for—their communities

See our [Philosophy](docs/PHILOSOPHY.md) for full values and design ethics.

---

## Development Setup

### Prerequisites

- Python 3.9 or higher
- Poetry for dependency management
- Git

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/bimdev1/NIMIK.git
   cd NIMIK
   ```

2. Install dependencies:
   ```bash
   poetry install
   ```

3. Set up pre-commit hooks:
   ```bash
   poetry run pre-commit install
   ```

### Development Workflow

1. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. Make your changes following our [Contributing Guidelines](docs/CONTRIBUTING.md)

3. Run tests:
   ```bash
   poetry run pytest
   ```

4. Submit a pull request

### Quality Checks

We maintain high standards for both technical and cultural safety:

- Code formatting with Black and isort
- Type checking with mypy
- Linting with ruff
- Cultural safety checks
- Accessibility verification
- Security scanning

---

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
└── scripts/                  # Utility scripts
```

## Key Documentation

| Category | Documentation |
|----------|--------------|
| Project Foundation | [Philosophy](docs/PHILOSOPHY.md), [Code of Conduct](docs/CODE_OF_CONDUCT.md) |
| Contributing | [Contributing Guidelines](docs/CONTRIBUTING.md), [Security Policy](.github/SECURITY.md) |
| Technical | [Technical Documentation](docs/technical/README.md) |
| Community | [Community Guidelines](docs/community/README.md) |
| Governance | [Governance Documentation](docs/governance/README.md) |

---

## Project Status

### Current Phase: Groundwork
- [x] Define modular architecture
- [x] Establish project structure
- [x] Set up development environment
- [x] Implement quality checks
- [ ] Begin core implementation
- [ ] Set up initial testing

See our [Project Board](https://github.com/bimdev1/NIMIK/projects/1) for detailed status.

---

## License

This project is released under the [MIT License](LICENSE).
We ask that all users and contributors respect the ethics outlined in our philosophy and code of conduct.

---

## Get Involved

This is a living, community-anchored project. To contribute:
1. Read our [Contributing Guidelines](docs/CONTRIBUTING.md)
2. Check our [Issues](https://github.com/bimdev1/NIMIK/issues)
3. Join our [Discussions](https://github.com/bimdev1/NIMIK/discussions)
4. Review our [Security Policy](.github/SECURITY.md)
