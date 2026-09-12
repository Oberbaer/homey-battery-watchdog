# Changelog

## Unreleased

_No unreleased changes yet._

## [1.0.0] - 2026-09-12

### Added

- Initial central battery-device watchdog proposal.
- Optional mobile push delivery to explicitly selected Homey users, alongside Timeline notifications.
- Portable Homey CLI module resolution and configurable read-only diagnostics.
- Automated GitHub Actions test workflow.
- Contribution guidelines.
- Public release and repository metadata.

### Changed

- The generated Flow uses a neutral public name and is disabled by default.
- The installer targets the `Battery Watchdog` Homey folder.
- Stale-device threshold is 24 hours; unchanged-fault notifications repeat every 6 hours.
- GitHub Actions use current Node 24-compatible action versions.
- README includes build, license and Node.js status badges.

### Fixed

- Notification suppression is saved only after successful delivery; unreliable legacy suppression is discarded.
- All affected devices are reported, including missing timestamps as monitoring unknown.
