# GIT-cheat-sheet


## Github CLI


### Download all repos from org:

```
gh repo list automationrevolution --limit 1000 | while read -r repo _; do
  gh repo clone "$repo" "$repo"
done
```