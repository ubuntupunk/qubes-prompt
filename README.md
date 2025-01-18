# Qubes OS Command Prompter | rofi / fzf launcher

<a href="https://www.buymeacoffee.com/ubuntupunk" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

This project provides two helpers to access to **Qubes commands** and **shortcuts** via an **interactive manual** extracted from the official GnuQUBES manual. 40 commands are made available from the QUBES code-base in this way, allowing users to reference and learn the craft of QUBES. Using the helpers may assist those wanting to learn more about QUBES. This version is for posix-compliant systems that are able to install fzf/rofi, a seperate ulauncher extension is also available.

## Versions

There are two versions to suit different user preferences:

1. **CLI Version**: Ideal for users who prefer interacting through the command line.
2. **Rofi Popup Version**: Designed for users who prefer a graphical interface, providing a visually appealing and intuitive experience, great for tiling window managers like [i3](https://i3wm.org/) and [bspwm](https://github.com/baskerville/bspwm).

## Usage

| Keyword        | Description                                                                    | Example     |
| -------------- | ------------------------------------------------------------------------------ | ----------- |
| ``qubes-fzf`` | Search for qubes**commands** and **shortcuts** for a given `query` | enter to open QUBES Manual |
| `qubes-rofi` | Search for qubes**commands** and **shortcuts** for a given `query` | enter to open QUBES Manual |

## Features

* Search for QUBES Commands either by their description or their Hotkey.
* Hitting enter on a command will redirect to [Qubes Manual](qubes.md) on the same command.

## Disclaimer
* This project is not related to the GnuPG Project and does not make any claims about the Qubes software.
* Since the Commands Database and its description fragments have not been fully tested and validated, they may not be functional, please report any issue here if any don't map the GnuPGP official manual.
* If you have issues with GnuPG (QUBES) please report that via the official QUBES channels.

## Installation

### Manual Installation

* Download the [Latest Release](https://github.com/ubuntpunk/qubes-prompt/releases/latest)
* Extract the archive and copy the files to `~/.local/share/qubes-prompt`

### System requirements
- Rofi
- Fzf
### Recommended Installation
```python
pip install qubes-prompt
```
### Install Helpers for Ubuntu/Debian

```bash
sudo apt install rofi fzf
```
### Operation
`qubes-fzf`  `# Uses fzf interface`

`qubes-rofi`  `# Uses rofi interface`



