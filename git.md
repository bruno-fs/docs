

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

## Submodules
```
bash
# add a submodule
git submodule add git@github.com:url_to/coolmodule.git path_to_submodule

# clone/update all submodules
git submodule update --init --recursive

# checkout all submodules to latest commit on master
git submodule foreach --recursive checkout master
```

## Split one big commit

https://stackoverflow.com/a/6217314



sources: 
- [SO](https://stackoverflow.com/questions/6474847/how-do-i-git-clone-recursive-and-checkout-master-on-all-submodules-in-a-single)
- [this gist](https://gist.github.com/gitaarik/8735255)
