git cards
=========

git init
========

Initialize a new git repo in the current working directory.

git clone <clone_url>
=====================

Clone an existng git repo.

git log
=======

Show history of changes.

git diff
========

Show changes to tracked files.

git status
==========

Show a list of changed files in the working directory.

git add <path/to/file>
======================

Add a new file to the current repo.

git add .
=========

Stage all new files and changes to tracked files for the current repo.

git add -u
==========

Stage all removed files and changes to tracked files for the current repo.

git add -A
==========

Stage all added files, removed files, and changes to tracked files for the current repo.

git commit -m <message>
=======================

Commit all your staged changes.

git commit --amend
==================

Amend your most recent commit with the current changes.

git tag v1.0
============

Mark a version or milestone.

git pull --rebase
=================

Fetch from origin and fast forward your changes on top of it.

git push
========

Push committed changes to origin.

git reset --hard
================

Discard all uncommitted changes in your working tree. Cannot be undone.

git checkout <path/to/file>
===========================

Reset an individual file back to HEAD.

git checkout <branch_name>
==========================

Switch branches.

git branch
==========

List all local branches for the current repo.

git branch -d <branch_name>
===========================

Delete a local branch.

git push origin :<branch_name>
==============================

Delete (really?) a remote branch.

git checkout branch2; git merge branch1
=======================================

Merge branch1 into branch2

git checkout -b new_branch old_branch
=====================================

Create new_branch based on old_branch and switch to it.

git push origin
===============

Push locally created branch to remote.

git stash
=========

Stash uncommitted changes in current working tree.

git stash pop
=============

Apply stashed changes to current working tree.

www.adamlowe.me
===============

Credit for the concept and the intial content.

