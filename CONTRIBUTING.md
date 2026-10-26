# Contributing to Octonary Robotics

Thanks for helping build mechanical tentacles, one segment at a time. This guide applies to every repository in the organization unless a repository provides its own `CONTRIBUTING.md`.

By taking part, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Ways to contribute

- **Report a bug** in software or firmware using the *Bug report* issue form.
- **Report a hardware issue** (mechanical, electrical, assembly) using the *Hardware issue* form.
- **Suggest an idea** using the *Feature request* form, or start a thread in Discussions.
- **Improve documentation**: typos, unclear steps, missing diagrams.
- **Submit code** through a pull request.

Looking for a first task? Filter issues by the `good first issue` label.

> **Security or safety problem?** Do not open a public issue. Follow [SECURITY.md](SECURITY.md) instead.

## Workflow

1. **Discuss first** for anything larger than a small fix. Comment on an existing issue or open a new one so we can agree on the approach before you spend time on it.
2. **Fork** the repository and create a branch from `main`:
   ```bash
   git checkout -b feat/short-description
   ```
   Use a prefix that matches the change: `feat/`, `fix/`, `docs/`, `refactor/`, `test/`, `chore/`.
3. **Make focused commits.** We follow [Conventional Commits](https://www.conventionalcommits.org/):
   ```
   feat(control): add tendon tension limiter
   fix(firmware): debounce segment 3 limit switch
   docs: clarify calibration steps
   ```
4. **Test your change.** Run the repository's test and lint commands (see its README). If you changed behaviour, add or update tests.
5. **Open a pull request** against `main` and fill in the template. Link the issue it resolves (`Closes #123`).
6. **Review.** A maintainer will review your pull request. Please respond to feedback by pushing new commits; we squash on merge.

## Working with hardware

Mechanical tentacles move with real force. When your change affects motion, actuation or power:

- Test in simulation first, then on hardware with reduced speed and torque limits.
- Keep an emergency stop within reach and the working area clear.
- Describe the test setup and results in your pull request (hardware revision, firmware version, what you observed).
- Never disable or bypass safety limits in a pull request without a clear explanation and maintainer agreement.

## Style

- Follow the formatter and linter configured in each repository; CI enforces them.
- Prefer clear names over comments; comment the *why*, not the *what*.
- Keep pull requests small enough to review in one sitting.
- Write documentation and commit messages in English.

## Licensing

Each repository states its license in its `LICENSE` file. By submitting a contribution, you agree that it may be distributed under that repository's license.

## Questions

See [SUPPORT.md](SUPPORT.md) for where to ask.
