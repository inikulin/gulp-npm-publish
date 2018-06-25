# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [3.2.0] - 2018-07-01
### Unreleased
- Check [Github status](https://developer.github.com/v3/repos/statuses/) as a new kind of validation

## [3.1.0] - 2018-06-21
### Added
- be able to run publish-please in dry mode

## [3.0.3] - 2018-06-20
### Fixed
- fix install on npm 3.10.10

## [3.0.2] - 2018-06-12
### Fixed
- Support vulnerability exceptions from .nsprc file

## [3.0.1] - 2018-06-05
### Fixed
- installation on windows platform

## [3.0.0] - 2018-05-30
### Security
- update direct dependencies flagged as `Critical` and `High` vulnerabilities by npm audit
- this update causes the following breaking change: publish-please must run on node version >= 6.0.0
