# my-nanorc

A readline/emacs keybindings set for nano.

## Installation

_Obs:_ DO NOT forget to **backup** your original nanorc configuration file.

1. You can download a .zip file or clone this repository with:

`git clone https://github.com/gabrielproencaalves/my-nanorc.git`

2. Go to the downloaded directory:

`cd my-nanorc`

3. Copy the '.nanorc' file to your home:

`cp .nanorc $HOME/.nanorc`

# Configuration

In some situations, you will be dissatisfied with the keys configured. Don't worry! Modifying the keyboard shortcuts is a very easy task. The basic syntax boils down to:

`bind KEY MENU`

Where:
    KEY: characters that represents a key combination, eg. `^a` for CTRL+a, or, `M-s` for Meta+s.
    MENU: the menu that receives the new keybinding setting, e.g., Main for the default editing screen.

Before every binding, I'd like to recommend to unbind it first, because if not, multiple unwanted commands/macros will be executed simultaneously.

`unbind KEY MENU`

See also nanorc(5) for more information.
