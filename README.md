> **Archived:** This project is no longer maintained as of May 2026.</br>
> It remains available for reference and personal use.</br>
> Successor project: https://github.com/pncolvr/dotfiles-quickshell

# Info

This is my personal daily driver waybar configuration that I use for personal and work activities.

# Relevant Commands
I use this repo as a git submodule on my dotfiles.  
The following command is isued on the dotfiles repo, to have this one as a submodule.
```shell
git submodule add git@github.com:pncolvr/dotfiles-waybar.git .config/waybar
```

## When cloning a "parent repo" to include the submodules

```shell
git clone --recurse-submodules <repository-url>
```
_or_ if we cloned the repo without the submodules
```shell
git submodule update --init --recursive
```

# Syncing submodules

```shell
git submodule sync --recursive
```
