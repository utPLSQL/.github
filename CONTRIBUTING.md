# Contributing to utPLSQL

Thank you for your interest in contributing! This document provides organisation-wide guidelines that apply to all utPLSQL repositories. Each repository may have additional, more specific contributing instructions in its own `CONTRIBUTING.md` or `README.md` — please read those too.

## Ways to Contribute

- **Report bugs** — open an issue using the bug report template
- **Suggest features** — start a [Discussion](https://github.com/orgs/utPLSQL/discussions) in the Ideas category
- **Fix bugs / implement features** — open a pull request
- **Improve documentation** — corrections and additions are always welcome
- **Answer questions** — help others on GitHub Discussions or Stack Overflow

## Before You Start

- Search existing issues, discussions, and pull requests to avoid duplicates.
- For significant changes, open a Discussion or issue first to align on the approach before investing time in implementation.

## Development Setup

Each repository has its own environment requirements and setup instructions in its `README.md` or `CONTRIBUTING.md`. In general:

1. Fork the repository and clone your fork.
2. Follow the setup steps described in that repository.
3. Create a branch from `develop` (not `main`/`master`):
   ```
   git checkout -b feature/my-feature develop
   ```

## Pull Request Guidelines

- Target the `develop` branch unless the repository instructs otherwise.
- Keep PRs focused — one feature or bug fix per PR.
- Add or update tests for any behaviour you change. PRs without adequate test coverage may be rejected.
- Ensure all existing tests pass before submitting.
- Write a clear PR description: what changed and why.
- Reference the related issue or discussion with `Closes #<number>` where applicable.

## Commit Messages

Use short, imperative-mood subject lines:
```
Fix null pointer in expectation reporter
Add support for nested suites
```

## Code Style

Follow the conventions already present in the repository you are contributing to. Repository-specific style guides (naming conventions, formatting rules, language idioms) take precedence over any general preference.

## Code of Conduct

This project follows our [Code of Conduct](CODE_OF_CONDUCT.md). By participating you agree to abide by its terms.

## License

By contributing you agree that your contributions will be licensed under the [Apache 2.0 License](https://github.com/utPLSQL/utPLSQL/blob/develop/LICENSE).
