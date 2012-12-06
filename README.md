# Jcemer dotfiles

![screenshot](https://raw.github.com/jcemer/dotfiles-mac/master/screenshot.png)

## Installation

```bash
git clone https://github.com/jcemer/dotfiles-mac.git && cd dotfiles-mac && ./bootstrap.sh
```

Check the original project for more info https://github.com/barkmadley/dotfiles-mac

## Sublime Text 2

Run the `bash` line below to make a symlink to `subl`. This will be used to open files and projects in Sublime Text 2.

```bash
ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" ~/bin/subl
```