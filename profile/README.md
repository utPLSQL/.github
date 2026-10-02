<p align="center">
  <img src="https://raw.githubusercontent.com/utPLSQL/utPLSQL-logo/main/utPLSQL-testing-framework-transparent_small_background.png" alt="utPLSQL — Unit Testing Framework for Oracle PL/SQL" width="600">
</p>

<!--start-include-in-doc-about-->
utPLSQL is a set of free-to-use, open-source frameworks and tools for unit testing Oracle Database PL/SQL code, inspired by the JUnit and RSpec family of frameworks.

It lets you write and run automated tests for anything that can be executed and observed from PL/SQL - packages,
functions, procedures, triggers, views, and beyond.

Tests are defined with simple annotations and can be structured into hierarchies of suites, making tests easier to
group into logical collections. A rich variety of matchers enables data comparison, including complex types such as objects,
collections and cursors, while automatic, configurable transaction control keeps every test isolated and repeatable.

Built-in code coverage reporting and multi-format test result reporting make utPLSQL easy to run within
existing CI/CD pipelines, with native integrations for SonarQube, Jenkins, TeamCity, Azure DevOps, GitHub Actions and more.

## Frameworks and tools
<!--start-frameworks-table-->
| Project                                                                       | Description                                                                                         | What's new?                                                             | Something broken?                                                               |
|-------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| [utPLSQL](https://github.com/utPLSQL/utPLSQL)                                 | Core framework — install and run unit tests in Oracle                                               | [releases](https://github.com/utPLSQL/utPLSQL/releases)                 | [report it here](https://github.com/utPLSQL/utPLSQL/issues/new)                 |
| [utPLSQL-cli](https://github.com/utPLSQL/utPLSQL-cli)                         | Command-line client for running tests from CI/CD pipelines                                          | [releases](https://github.com/utPLSQL/utPLSQL-cli/releases)             | [report it here](https://github.com/utPLSQL/utPLSQL-cli/issues/new)             |
| [utPLSQL-maven-plugin](https://github.com/utPLSQL/utPLSQL-maven-plugin)       | Maven plugin for running utPLSQL tests                                                              | [releases](https://github.com/utPLSQL/utPLSQL-maven-plugin/releases)    | [report it here](https://github.com/utPLSQL/utPLSQL-maven-plugin/issues/new)    |
| [utPLSQL-SQLDeveloper](https://github.com/utPLSQL/utPLSQL-SQLDeveloper)       | SQL Developer extension                                                                             | [releases](https://github.com/utPLSQL/utPLSQL-SQLDeveloper/releases)    | [report it here](https://github.com/utPLSQL/utPLSQL-SQLDeveloper/issues/new)    |
| [utPLSQL-PLSQL-Developer](https://github.com/utPLSQL/utPLSQL-PLSQL-Developer) | PL/SQL Developer extension                                                                          | [releases](https://github.com/utPLSQL/utPLSQL-PLSQL-Developer/releases) | [report it here](https://github.com/utPLSQL/utPLSQL-PLSQL-Developer/issues/new) |
| [utPLSQL-java-api](https://github.com/utPLSQL/utPLSQL-java-api)               | Java API for connecting to utPLSQL                                                                  | [releases](https://github.com/utPLSQL/utPLSQL-java-api/releases)        | [report it here](https://github.com/utPLSQL/utPLSQL-java-api/issues/new)        |
| [utPLSQL-dotnet-api](https://github.com/utPLSQL/utPLSQL-dotnet-api)           | .NET API for connecting to utPLSQL                                                                  |                                                                         | [report it here](https://github.com/utPLSQL/utPLSQL-dotnet-api/issues/new)      |
| [utPLSQL-demo-project](https://github.com/utPLSQL/utPLSQL-demo-project)       | Demonstration project showcasing running utPLSQL tests in GitHub Actions with dockerized Oracle DB  |                                                                         | [report it here](https://github.com/utPLSQL/utPLSQL-demo-project/issues/new)    |
<!--end-frameworks-table-->


## Community

utPLSQL is created by a community of passionate engineers and embraces a 
[Code of Conduct](https://github.com/utPLSQL/.github/blob/main/CODE_OF_CONDUCT.md).

* Search or start a topic at the [Organization](https://github.com/orgs/utPLSQL/discussions) or [the utPLSQL framework](https://github.com/utPLSQL/utPLSQL/discussions) GitHub Discussions to ask questions, find support and share ideas
* Search [Stack Overflow](https://stackoverflow.com/questions/tagged/utplsql) using the `utplsql` tag
* Open a new [issue on GitHub](https://github.com/utPLSQL/utPLSQL/issues) for bugs or feature requests
* Read the [contributing guide](https://github.com/utPLSQL/utPLSQL/blob/develop/CONTRIBUTING.md) if you'd like to get involved

Follow the project on [X](https://x.com/utPLSQL), [Bluesky](https://bsky.app/profile/utplsql.org)
and [LinkedIn](https://www.linkedin.com/company/utplsql/) for news and announcements.

## License

utPLSQL projects are licensed under the [Apache 2.0 license](https://github.com/utPLSQL/utPLSQL/blob/develop/LICENSE).

## Stewardship

utPLSQL is stewarded by utPLSQL Development Labs Ltd, which holds the utPLSQL name, branding and project assets, and manages sponsorships and funded development.
Contributors retain copyright of their contributions, which are licensed under the Apache 2.0 license.
See the [announcement](https://www.utplsql.org/announcements/incorporation-of-utplsql-development-labs-ltd.html) for details.
<!--end-include-in-doc-about-->

## Getting Started

- [Documentation](https://utplsql.org/utPLSQL/)
- [Quick Start Guide](https://utplsql.org/utPLSQL/latest/userguide/getting-started.html)
- [Installation](https://utplsql.org/utPLSQL/latest/userguide/install.html)

See the full [About page](https://www.utplsql.org/about.html) for project history, contributors and supporters.

## Contributing

Contributions are welcome! See [CONTRIBUTING.md](../CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](../CODE_OF_CONDUCT.md) for guidelines.

