# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## API
The API consists of all public Java types from `com.atlassian.performance.tools.virtualusers.api` and its subpackages:

  * [source compatibility]
  * [binary compatibility]
  * [behavioral compatibility] with behavioral contracts expressed via Javadoc

[source compatibility]: http://cr.openjdk.java.net/~darcy/OpenJdkDevGuide/OpenJdkDevelopersGuide.v0.777.html#source_compatibility
[binary compatibility]: http://cr.openjdk.java.net/~darcy/OpenJdkDevGuide/OpenJdkDevelopersGuide.v0.777.html#binary_compatibility
[behavioral compatibility]: http://cr.openjdk.java.net/~darcy/OpenJdkDevGuide/OpenJdkDevelopersGuide.v0.777.html#behavioral_compatibility

### POM
Changing the license is breaking a contract.
Adding a requirement of a major version of a dependency is breaking a contract.
Dropping a requirement of a major version of a dependency is a new contract.

## [Unreleased]
[Unreleased]: https://bitbucket.org/atlassian/virtual-users/branches/compare/release-1.0.0%0Dmaster

## [1.0.1] - 2018-09-05
[1.0.1]: https://bitbucket.org/atlassian/virtual-users/branches/compare/release-1.0.1%0Drelease-1.0.0
**Botched version** please avoid

### Changed
- `VirtualUserOptions` API

## [1.0.0] - 2018-09-04
[1.0.0]: https://bitbucket.org/atlassian/virtual-users/branches/compare/release-1.0.0%0Drelease-0.0.4

### Changed 
- Define public API for the module

### Added
- API for virtual users JAR command line arguments.

### Fixed
- Strict dependency resolution.

## [0.0.4] - 2018-08-28
[0.0.4]: https://bitbucket.org/atlassian/virtual-users/branches/compare/release-0.0.4%0Drelease-0.0.3

### Removed
- Remove plain text report.

### Added
- Add diagnosticsLimit parameter.

## [0.0.3] - 2018-08-07
[0.0.3]: https://bitbucket.org/atlassian/virtual-users/branches/compare/release-0.0.3%0Drelease-0.0.2

### Fixed
- Restore main log. See #2.

## [0.0.2] - 2018-08-03
[0.0.2]: https://bitbucket.org/atlassian/virtual-users/branches/compare/release-0.0.2%0Drelease-0.0.1

### Fixed
- Gradle plugin to compile Kotlin source.

## [0.0.1] - 2018-08-03
[0.0.1]: https://bitbucket.org/atlassian/virtual-users/branches/compare/release-0.0.1%0Dinitial-commit

### Added
- Generic Virtual Users mechanisms migrated from [JPT submodule].
- [README.md](README.md).
- Bitbucket Pipelines.

[JPT submodule]: https://stash.atlassian.com/projects/JIRASERVER/repos/jira-performance-tests/browse/virtual-users?at=ce7ab255e955891a927ac1c19b9b6178b56d1e4f
