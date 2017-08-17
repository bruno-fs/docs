

## Destroy commits not pushed

~~~bash
# delete last 4 commits
git reset --hard HEAD~4
# delete all commits after <SHA>

git reset --hard <SHA>

# delete all unpushed commits
git reset --hard <REMOTE>/<BRANCH_NAME>

~~~
source: [SO](https://stackoverflow.com/a/16820875/6200095)
