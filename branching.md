= Branching and Tagging
== How do you make a branch?
A branch is a "movable pointer to a commit"

```
git branch <branchname>
```
will create a new branch named <branchname>.

== What is the difference between a branch and a commit?
A branch is a "movable pointer to a commit". A commit is a stored snapshot, saved in the repo 

== What is a tracking branch?
A tracking branch is a local branch that has a direct relationship to a remote branch. When you push while on a tracking branch, git automatically knows which server (remote) and branch to push to.

== How do you setup a tracking branch? *
```
git checkout -b <branch> <remote>/<branch>
-or-
git checkout --track <remote>/<branch>
```

== How do you make a tag?
```
git tag 
```
== How do you push a tag to a remote?
```
git push --tags <remote> <branch>
```

== What is the difference between a branch and a tag?
== How does one view all branches? Tags? Across all remotes?
View all branches:
```
git branch
```

View all tags:
```

```


== How do I delete a remote branch? *
