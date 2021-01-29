title: Git Gud - Tips and Tricks
author:
name: James Freeman
twitter: developervert
url: https://jammaloo.com
output: index.html
style: git-style.css

--

# Git Gud
## Hidden tricks that can save you time

--

<img src="git-gud.png" style="height: 70vh;">

--

# What we think git is

--

```bash
➜  git_goodness git:(develop) git merge my_branch
Auto-merging there
CONFLICT (content): Merge conflict in there
Auto-merging hi
CONFLICT (content): Merge conflict in hi
Automatic merge failed; fix conflicts and then commit the result.
➜  git_goodness git:(develop) ✗ git pull
error: Pulling is not possible because you have unmerged files.
        hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
        fatal: Exiting because of an unresolved conflict.
```

--

# What git actually is

--

```console
➜  git_goodness git:(develop) git merge my_branch
Auto-merging there
CONFLICT (content): Merge conflict in there
Auto-merging hi
CONFLICT (content): Merge conflict in hi
Automatic merge failed; fix conflicts and then commit the result.
➜  git_goodness git:(develop) ✗ git pull
error: Pulling is not possible because you have unmerged files.
        hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
        fatal: Exiting because of an unresolved conflict.
```

--

<img src="same.png" style="width: 60vw;">

--

### Git is hard

Git is complex, but it has some nice features

* Conditional Configs
* Patch Mode
* Bisects
* Change based searches
* Blame

--
