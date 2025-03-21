# Add, commit, push in a single command

```
git config --global alias.acomp '!git add . && git commit -m "$1" && git push origin $(git branch --show-current)'

git acomp "initial"
```


```
git config --global alias.sync-note '!git add . && git commit -m "sync-note: $(date +"%Y-%m-%d %H:%M:%S")" && git push origin $(git branch --show-current)'

git sync-note
```