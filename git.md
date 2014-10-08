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
Git include my_file
```

Include changes in a file into the next work chunk 
==============================================

```
Git include my_file
```

This includes the changes to that file in a list of changes
currently scheduled to be included in the next work chunk.

Include all scheduled changes into a work chunk
===============================================

```
Git chunk -m "Journal entry"
```

Store all scheduled changes in a new chunk
==========================================

```
Git include --uptodate
```

Include all changes *and* chunk them
====================================

```
Git chunk -am "Journal entry"
```

View list of recent chunks
==========================

```
Git journal
```

Transmit chunks to remote chunkstore
====================================

```
Git transmit
```

Fetch chunks from remote chunkstore
===================================

```
Git download
```
