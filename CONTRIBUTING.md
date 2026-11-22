# Contributing to Night404

Thank you for helping improve Night404. The theme is built around a distinct nighttime palette, readable technical notes and CSS-only customization.

## Reporting issues

Open a GitHub issue with the theme version, Obsidian version (and installer version if available), operating system, editor mode, relevant Style Settings values, and steps to reproduce. Include a minimal Markdown example and a screenshot when useful. Disable unrelated CSS snippets and plugins to isolate the issue, if possible. Remove private vault content and personal information before sharing screenshots.

## Local development

Fork and clone the repository, then create a branch for your change. Use a separate test vault. Copy `theme.css` and `manifest.json` into the vault's `.obsidian/themes/Night404/` directory, or symlink that directory to your local checkout on systems that support it.

Keep changes focused. Preserve the original palette unless a change is explicitly agreed upon. Prefer native Obsidian CSS variables and scoped selectors over `!important`. Keep Style Settings optional and preserve usable defaults without plugins. Avoid unnecessary animations and external resources.

## Testing

Before submitting a pull request, check:

- Reading View, Live Preview and Source Mode.
- H1–H6, multiline headings, bold, italic, inline code, tags, highlights and links.
- Fenced code with both backgrounds and all code customization settings.
- Folder names, active and inactive files and tabs, note titles and rename interactions.
- Callout variants, nested callouts, Canvas colors and focused nodes.
- Style Settings enabled and disabled, including individual gradient switches.
- Desktop and mobile where available; report platforms and versions not tested.
- `git diff --check` and `grep -n '!important' theme.css` (no matches expected).

Include a description of the change, tests performed and before/after screenshots for visual changes. Do not change the version number or publish a release as part of an ordinary contribution.

By contributing, you agree that your contribution is distributed under the repository's MIT license.
