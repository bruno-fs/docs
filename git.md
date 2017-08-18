

## Destroy commits not pushed

```bash
# delete last 4 commits
git reset --hard HEAD~4

# delete all commits after <SHA>
git reset --hard <SHA>

# delete all unpushed commits
git reset --hard <REMOTE>/<BRANCH_NAME>

```
source: [SO](https://stackoverflow.com/a/16820875/6200095)


## Pick a file from another branch

```bash
git checkout <other-branch> <path/to/file>


```
source: [Jason Rudolph blog](http://jasonrudolph.com/blog/2009/02/25/git-tip-how-to-merge-specific-files-from-another-branch/)
