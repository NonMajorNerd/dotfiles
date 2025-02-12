# NMN DotFiles

> [!Warning] Disclaimer;
> I don't know what I'm doing.
> Use at your own risk, and make a backup first.

![Screenshot](/tmuxvireadme.png?raw=true)

## Installing
1. Backup any config file(s) you plan to overwrite.
2. Clone this repo into your chosen directory with<br>
``` gh repo clone nonmajornerd/dotfiles ~/conf ```
3. Create a symlink for each config desired.<br>
For example to use my config file for vi;<br>
``` ln -sf ~/conf.exrc .exrc ```

## Updating
1. Updating the repo will update all existing symlinks.
```
cd ~/conf
gh repo sync
```

## Index

- _**File** - Package_
- **.exrc** - [vi](https://ibm.com/docs/en/power6?topic=commands-vi-command)
- **.tmux.conf** - [Tmux](https://github.com/tmux/tmux/wiki)
