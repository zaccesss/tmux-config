# Contributing

Thanks for taking an interest. Contributions are welcome: config fixes, binding corrections
and guide improvements.

## What belongs here

- A wrong option or binding
- A plugin that no longer loads on current tmux
- Improvements to the guides
- Improvements to the guides

## What does not belong here

- A binding or plugin that only reflects one person's taste rather than something broadly
  useful, keep that in your own copy

## How to contribute

1. Fork the repository and create a branch named `fix/<short-description>` or
   `feat/<short-description>`.
2. Make your change and check it loads: `tmux -f tmux.conf new-session -d -s test` should start
   a session with no error.
3. Open a pull request with a clear title and a one-paragraph description of what changed and
   why. CI starts a session with the config.

## Style rules

> [!IMPORTANT]
> - **Comments**: explain the why, not the what.
> - **UK English** in prose and documentation.

## Reporting bugs

Open an issue with your tmux version and platform, what you expected versus what happened.

More about me and my work: [isaacadjei.me](https://isaacadjei.me).
