# GIT-cheat-sheet


### Download all repos from org:

### Github CLI

gh repo list automationrevolution --limit 1000 | while read -r repo _; do
  gh repo clone "$repo" "$repo"
done