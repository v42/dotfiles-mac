# Dotfiles and more

![screenshot](https://raw.github.com/jcemer/dotfiles-mac/master/screenshot.png)

## Installation

```bash
git clone https://github.com/jcemer/dotfiles-mac.git && cd dotfiles-mac && ./bootstrap.sh
```

See the original project for more info: https://github.com/barkmadley/dotfiles-mac

## Tomorrow Theme

Theme loosely based on [Tomorrow Theme](https://github.com/chriskempson/tomorrow-theme). The main change is to use `Droid Sans Mono 15 pt.` as font.

Run `tomorrow.terminal` and set it as your default profile.

## Sublime Text 2

Run the `bash` line below to make a symlink to `subl`. This will be used to open files and projects in Sublime Text 2.

```bash
ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" ~/bin/subl
```