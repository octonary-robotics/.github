# .github

Organization-wide files for **Octonary Robotics**.

| Path | Purpose |
|---|---|
| [`profile/README.md`](profile/README.md) | The public organization profile shown at [github.com/octonary-robotics](https://github.com/octonary-robotics) |
| [`profile/assets/`](profile/assets) | Animated SVG artwork used by the profile (light and dark variants) |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | How to contribute to any Octonary repository |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | Community standards and how they are enforced |
| [`SECURITY.md`](SECURITY.md) | How to report vulnerabilities and safety issues privately |
| [`SUPPORT.md`](SUPPORT.md) | Where to ask questions and get help |
| [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE) | Default issue forms: bug, hardware issue, feature request |
| [`.github/PULL_REQUEST_TEMPLATE.md`](.github/PULL_REQUEST_TEMPLATE.md) | Default pull request checklist |

GitHub applies these community health files to every repository in the organization that does not define its own. A repository can override any of them by adding a file with the same name.

## Editing the profile

- The profile renders from `profile/README.md` on the default branch (`main`).
- Images are referenced by absolute `raw.githubusercontent.com` URLs, so changes to `profile/assets/` appear once they are merged into `main`.
- Each artwork file has a `-light` and a `-dark` version. Keep both in sync; the profile switches between them with `<picture>` and `prefers-color-scheme`.
- GitHub strips `<style>` tags and `style` attributes from Markdown. All CSS and animation lives inside the SVG files.

## Brand

| Token | Hex | Use |
|---|---|---|
| Graphite | `#1B1F24` | Mark and text on light backgrounds |
| Paper | `#F4F3EF` | Light background; mark on dark backgrounds |
| Night | `#14171B` | Dark background |
| Carbon | `#2A2F36` | Dark surfaces and dividers |
| Slate | `#5B6068` | Secondary text on light backgrounds |
| Silver | `#A9AEB5` | Secondary text on dark backgrounds |
| Stone | `#D9D7D0` | Dividers and borders on light backgrounds |

Typeface: [Sora](https://fonts.google.com/specimen/Sora) (wordmark: SemiBold 600, −1% tracking).
