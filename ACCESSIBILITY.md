# Accessibility

The bindings keep tmux's defaults where tutorials rely on them and shorten the actions used most. The status bar is plain and high contrast.

## Vision

- The status bar uses light grey (colour 250) on black, a contrast ratio of about 11:1.
- True colour is forced on for every pane, so Neovim's colour scheme keeps its intended contrast inside tmux.
- Windows and panes are numbered from 1, matching how they are counted on the status bar.

## Keyboard and motor

- The prefix stays at tmux's default `Ctrl+B`, so every tutorial and cheat sheet still applies.
- `h`, `j`, `k` and `l` move between panes, the same letters [neovim-config](https://github.com/zaccesss/neovim-config) uses for windows.
- Resizing with `H`, `J`, `K` and `L` repeats while the key is held, without pressing the prefix again each time.
- `|` and `-` split panes, matching the shape of the split.
- Mouse support is on, so a pane can be clicked into or resized by dragging instead of with a key chord.
- Esc reacts after 10 ms rather than 500 ms, so it never lags in Neovim.
- Sessions save every 15 minutes and come back after a restart, so a layout never has to be rebuilt by hand.

## Feedback wanted

If something here gets in the way, open an [issue](https://github.com/zaccesss/tmux-config/issues/new/choose) describing what happened and what would work better.
