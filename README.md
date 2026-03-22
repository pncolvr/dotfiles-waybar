# Relevant Commands
I use this repo as a git submodule on my dotfiles.
The following command is isued on the "parent" repo, to have it as a submodule.
```shell
git submodule add git@github.com:pncolvr/waybar.git .config/waybar
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