# Changelog

All notable changes to this project are recorded here.

Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).
Versioning follows [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [Unreleased]

### Added

- Tabs are coloured by window name: editor cyan, git green, search yellow, shell magenta and blue for anything else. The current tab is a solid block of its colour, bold and marked with `*`.
- Screenshots and short animations of the config in action, dark and light, in the README's In action section.

### Changed

- The status bar takes the terminal's own background and text colours instead of a fixed black bar, so it stays high contrast in light and dark mode. The current window is bold and reversed.
- `ACCESSIBILITY.md`: a note that the settings are preferences, a callout for the plugins session restore depends on and a link to the shared accessibility statement.

### Added

- Initial release: tmux config with vi-style copy mode and pane navigation, a plain status bar
  and TPM plugins
- Setup and reference guides
- CI that starts a session with the config
- `ACCESSIBILITY.md`: the high-contrast status bar and short, consistent bindings.

### Changed

- Tidied code comments and the contributor guide.
