# sw1pr0g's dotfiles

## Contents

- all my `brew` dependencies including: applications, fonts, etc. See [`Brewfile`](https://github.com/sw1pr0g/dotfiles/blob/dev/macos/Brewfile)
- all my `macos` settings. See [`macos`](https://github.com/sw1pr0g/dotfiles/blob/dev/macos/settings.sh)
- all my shell configuration. See [`shell/`](https://github.com/sw1pr0g/dotfiles/tree/dev/shell) and [`config/zshrc`](https://github.com/sw1pr0g/dotfiles/blob/dev/config/zshrc)
- all my `vscode` configuration. See [`vscode/`](https://github.com/sw1pr0g/dotfiles/tree/dev/vscode)

## Installation

I am using [`dotbot`](https://github.com/anishathalye/dotbot/)
to set things up. Steps:

0. Decide what you want to install: comment out `run_dotbot 'steps/...'` that you don't need
1. Clone this repo with: `git clone https://github.com/sw1pr0g/dotfiles .dotfiles`
2. `cd .dotfiles/`
3. Run: [`bash ./install`](https://github.com/sw1pr0g/dotfiles/blob/dev/install)

## Local configuration

Some of the used tools requires local configuration. Such as `git` with username and email.

Here's the full list:

1. `~/.gitconfig_local` to store any user-specific data
2. `~/.shell_env_local` to store local shell config, like: usernames, passwords, tokens, `gpg` keys and so on


## License

[WTFPL](http://www.wtfpl.net) - DO WHAT THE FUCK YOU WANT TO
