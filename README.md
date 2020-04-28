# 2020-04-24-git-oreilly -  Notes
Git Workshop


- git clone <URL>: downloads the repo from web to PC
  - Make sure you do not nest repos, only run git clone once
  - just like git init only do it once per repo

git add README.md

git commit -m "add notes"

git push <where> <what> = git push origin master

## Branches

Git Branching

* Section off work, try code, collaborate on your own bit, so someone else can work on master, or do another branch
* Also keeps working state of code on master branch and all tests on branches.
* Can merge branches into master.
* To get from master to a branch can use - branch/switch/checkout

git checkout -b my_second_branch - create a branch and switch to it

git switch -c my_second_branch - create a branch and switch to it (switch is a new command)

git branch my_first_branch - create a branch

Rebaseing or incorporate branch updates

git rebase <branch> : if branch is master, replay current branch off of master
- will auto merge if possible
- helps deal with conflicts
