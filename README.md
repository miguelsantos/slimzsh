Miguel's slimzsh fork
=====================

This is a fork of slimzsh, a lean zsh configuration framework.
It can be found [here](https://github.com/changs/slimzsh).

# Fork

This repo is a submodule of my [dotfiles](https://github.com/miguelsantos/dotfiles), being part of the zsh configuration.

# Workflow

1. To bump the submodules (pure and zsh-syntax-highlight) do: `git submodule update --remote`
2. When working on this as a submodule, don't `git push` directly, go to the top project dir, commit the changes and then `git push --recurse-submodules=on-demand` to publish them at the same time
