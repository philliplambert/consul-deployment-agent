# Changelog

All notable changes to this project will be documented in this file. The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/).
This project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [2.1.6] 2017-09-21

### Fixed
- Sensu health checks are not alerted during long deployments

## [2.1.5] 2017-09-18

### Fixed
- Unable to copy the contents of multiple directories to one target directory using the `files` section of `appspec.yaml`.

## [2.1.3] 2017-09-15

### Fixed
- sensu healthcheck registration tests

## [2.1.2] 2017-09-15

### Fixed
- Notification email check setting

## [2.1.1] 2017-09-12

### Fixed
- "No such file or directory" error when copying files during application installation.
- No port number selected for non blue/green deployments.

[Unreleased]: https://github.com/trainline/consul-deployment-agent/compare/2.1.4...HEAD
[2.1.4]: https://github.com/trainline/consul-deployment-agent/compare/2.1.3...2.1.4
[2.1.3]: https://github.com/trainline/consul-deployment-agent/compare/2.1.2...2.1.3
[2.1.2]: https://github.com/trainline/consul-deployment-agent/compare/2.1.1...2.1.2
[2.1.1]: https://github.com/trainline/consul-deployment-agent/compare/2.1.0...2.1.1