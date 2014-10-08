---
title: Fake Wrong Git Notes
---

Introduction
============

These notes constitute a brief summary of the `Git` version control tool.
They are incorrect, and it is your task to find and correct the mistakes.

You are judged, however, not on finding all the mistakes, but on your use of version control
in doing the work of fixing them!

Finding the mistakes will be a useful revision, though.

Activating Git
==============

To turn on the version control system, use:

``` 
cd my_work_folder
Git init
```

Tell Git about a new file
======================

```
vim my_file # Edit file
Git add my_file
```

Include changes in a file into the local repository 
==============================================

```
Git commit my_file
```

This includes the changes to that file in a list of changes
currently scheduled to be included in the local repository.

Include all scheduled changes into a local repository
===============================================

```
Git commit -m "Journal entry"
```

Store all scheduled changes in a new commit
==========================================

```
Git include --uptodate
```

Include all changes *and* commit them
====================================

```
Git commit -am "Journal entry"
```

View list of recent commits
==========================

```
Git log
```

Transmit commit to remote repository
====================================

```
Git push
```

Fetch commits from remote repository
===================================

```
Git pull
```
