# Changelog

All Notable changes to `oauth2-github` will be documented in this file.

## 3.1.1 - 2024-09-03

### Fixed

- Corrected scope to get user email (#26)

## 3.1.0 - 2022-11-04

### Added

- Added work around to get user email with resource owner (#20)
- Added scope `user.email` to default scopes (#20)

## 3.0.0 - 2021-05-10

### Fixed

- Fixed documented return type for GithubResourceOwner::getId() (#17)

### Changed

- Change required PHP version to ^7.3 || ^8.0
- Switched from TravisCI to Github Actions
- Updated testing for newer PHPUnit, etc

## 2.0.0 - 2017-01-25

### Added
- PHP 7.1 Support

### Deprecated
- Nothing

### Fixed
- Nothing

### Removed
- PHP 5.5 Support

### Security
- Nothing

## 1.0.0 - 2017-01-25

Bump for base package parity

## 0.2.2 - 2016-11-21

### Added
- Update base package version from 1.0 to 1.4
- Update GithubResourceOwner to utilize ArrayAccessorTrait from base package

### Deprecated
- Nothing

### Fixed
- Nothing

### Removed
- Nothing

### Security
- Nothing

## 0.2.1 - 2016-04-13

### Added
- Support OAuth exceptions from Github with non-standard status codes (https://developer.github.com/v3/oauth/#common-errors-for-the-access-token-request)

### Deprecated
- Nothing

### Fixed
- Nothing

### Removed
- Nothing

### Security
- Nothing

## 0.2.0 - 2015-08-20

### Added
- Upgrade to support version 1.0 release of core client

### Deprecated
- Nothing

### Fixed
- Nothing

### Removed
- Nothing

### Security
- Nothing

## 0.1.0 - 2015-04-13

### Added
- Initial release!

### Deprecated
- Nothing

### Fixed
- Nothing

### Removed
- Nothing

### Security
- Nothing
