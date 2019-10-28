# Dotfiles

This setups everything on my MacBook Pro.
It is not yet fully automated,
but it is a very good first step.

## Installation

This steps need to be done to install everything:

1. Sign in to the App store
1. Run `install`
```
./install.sh
```

## Development

To add OSX settings, I usually manual set the setting and the see the changes in my defaults.
I then reset and write the commands for my scripts.

```
defaults read > before
defaults read > after
diff before after
```

## Things to do

* Setup Magnet configuration
* Setup Desktop & Desktop shortcuts
* Hotkey to switch input sources
* Remove hotkey for man page terminal

## Credits

This was inspired by a presentation from JHKuperus.
Example repositories:
- https://github.com/jhkuperus/dotfiles
- https://github.com/jqno/dotfiles