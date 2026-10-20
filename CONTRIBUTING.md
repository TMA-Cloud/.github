# Contributing

Thanks for your interest in TMA Cloud. This page explains how to report a problem and how to send a change to any of our repositories.

## Filing an issue

When reporting a bug, include your TMA Cloud version, how you run it (Docker or manual), steps to reproduce, and any relevant logs. In the app, **Settings** → **About** → **Copy details** copies the versions for you.

**Found a security issue?** Don't open a public issue. See [SECURITY.md](SECURITY.md).

## Making a pull request

- **Open an issue first** for a feature or anything bigger than a small fix, so we can agree on the approach before you spend time on it. Typos and small fixes need no issue.
- **Run the repository's checks** before you push. Its README says how to build and test it; for the app, turn on the hooks with `make hooks` and run `cargo xtask ci`.
- **Sign off each commit** with `git commit -s`. Write the subject in the imperative ("Fix the Shared listing query"), and say in the body what was wrong and why the change fixes it.
- **Update the docs** in the [Wiki](https://github.com/TMA-Cloud/Wiki) when the change is something users see.

## Conduct

This project follows the [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold it.

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](https://github.com/TMA-Cloud/TMA/blob/main/LICENSE).
