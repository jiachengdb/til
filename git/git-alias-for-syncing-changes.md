# Add, commit, push in a single command

```
git config --global alias.acomp '!f() { git add . && git commit -m "$1" && git push origin $(git branch --show-current); }; f'

git acomp "initial"
```