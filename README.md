
# Usage

install chezmoi and your dotfiles with the single command:
```sh
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply git@github.com:platane/chezmoi
```

```sh
# add a config file
chezmoi add <file>

# update config files
chezmoi re-add

# push changes
chezmoi cd
git add .
git commit -m .
git push
```
