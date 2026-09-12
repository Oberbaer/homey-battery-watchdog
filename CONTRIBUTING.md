# Contributing

Thanks for your interest in Homey Battery Watchdog.

Bug reports, improvement ideas and pull requests are welcome.

## Development

1. Fork or clone the repository.
2. Create a branch for your change.
3. Keep changes focused and easy to review.
4. Run the test suite before submitting changes:

```sh
npm test
```

5. Open a pull request and explain what changed and why.

## Privacy and security

Please do not commit:

- Homey access tokens or credentials
- real Homey device, Flow, folder or user IDs
- local machine paths
- generated runtime artifacts
- personal or production configuration

Use example values in documentation and tests.

## Safety

Changes affecting live Homey behavior should preserve the project's safe defaults:

- generated Flows stay disabled by default
- live changes require explicit approval
- diagnostics should be read-only unless clearly documented otherwise
- production identifiers remain outside the repository

## Code style

Prefer:

- small and understandable changes
- descriptive commit messages
- readable code
- tests for behavior changes
- clear documentation

Thanks for helping improve the project.
