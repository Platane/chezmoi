
# Usage

install chezmoi and your dotfiles with the single command:
```sh
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --ssh --apply platane
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
