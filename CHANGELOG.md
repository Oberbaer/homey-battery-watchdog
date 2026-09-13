# Changelog

## Unreleased

### Added

- `Homey_Watchdog`, a native Homey Pro app combining health diagnostics with scheduled battery-device silence monitoring.
- Local settings dashboard, Flow cards, owner-only APIs and device exclusions.
- Privacy, security, scoring and Homey Store documentation for the app.
- Dedicated unit tests and Homey publish-level validation.

### Changed

- CI now uses Node.js 24.
- CI now tests, validates and builds the bundled Homey Watchdog app.
- Public repository version prepared for v1.1.0.

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
