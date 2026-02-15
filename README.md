# My Dotfiles

Managed with [chezmoi](https://www.chezmoi.io/).

## Quick Setup on New Machine

```bash
# Install chezmoi and apply dotfiles
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply yourusername
```

## Requirements

- macOS or Linux
- git
- age (for encrypted files)

## Structure

- `.gitconfig*` - Git configurations with multi-account support
- `.zshrc` - Zsh configuration with oh-my-zsh
- `.p10k.zsh` - Powerlevel10k theme configuration
- `.ssh/config` - SSH configuration for multiple GitHub accounts (encrypted)

## Directory Organization

```
~/personal/  - Personal projects (uses personal git config)
~/sap/       - SAP/work projects (uses work git config)
```
