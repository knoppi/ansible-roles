# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

## [2.0.5] - 2020-11-12
### Added
- Handle list configs parameters

## [2.0.4] - 2020-10-09
### Added
- Lookup to handle arrays in configs

## [2.0.3] - 2020-08-28
### Changed
- Explicit file permissions

## [2.0.2] - 2020-02-13
### Added
- Tags for each tasks, with the format `manala_rolename.taskname`

## [2.0.1] - 2019-11-29
### Changed
- Update 'lookup' to use 'query'
- Minimum required version of ansible up to 2.5.0

## [2.0.0] - 2019-11-21
### Removed
- Debian wheezy support

### Added
- Handle configs states (present|absent) & raw content

## [1.0.6] - 2019-10-24
### Added
- Debian buster support

## [1.0.5] - 2019-05-21
### Changed
- Turn off scp upload & cdrw burning methods by default
- Configs templates are now inherited from a base one

## [1.0.4] - 2018-11-12
### Changed
- Update to Backup Manager 0.7.14 configs templates

## [1.0.3] - 2018-10-17
### Fixed
- Python 3 compatibility

## [1.0.2] - 2018-06-05
### Added
- Handle dependency packages to install

### Changed
- Replace deprecated uses of "include"
- Use native config template default values type when possible
- Allow S3 configuration for MySQL and PGSQL
- Pass apt module packages list directly to the `name` option

## [1.0.1] - 2017-12-06
### Added
- Debian stretch support

## [1.0.0] - 2017-01-09
### Added
- Handle installation
- Handle configs
