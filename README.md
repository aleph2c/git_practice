# git_practice

To configure your git command to [present a nice history](https://stackoverflow.com/a/45991969)
```
git config --global alias.hist "log --graph --date-order --date=short \
--pretty=format:'%C(auto)%h%d %C(reset)%s %C(bold blue)%ce %C(reset)%C(green)%cr (%cd)'"
```
