# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [2.0.0] - 2025-07-16

### Updated
- Update magento-cache-clean to new mage-os repo location [PR #1](https://github.com/markshust/magento2-metapackage-devtools-cli/pull/1)

### Removed
- Removed `composer.lock` file. This lets version constraints defined within `composer.json` take precedence to allow for package updates, but without locking users into the specific versions defined in a lock file.

## [1.0.0] - 2020-01-29

### Added
- Initial release.
