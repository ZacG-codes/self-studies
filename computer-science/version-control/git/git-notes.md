# Git/GitHub Notes

## What is Git?

Git is a version control system that records changes to files so that you can see and work with version history

This allows for
- reverson of files back to a previous state
- revision of the entire project back to a previous state
- comparison of changes over time
- the ability to recover from messed up or lost files

Git is a distributed version control system (DVCS)
- clients fully mirror the repository of the central server
- if the server goes down, any client can copy their repo back up to the server

## What Sets Git Apart

The primary difference between Git and other VCS is the way Git conceptualizes data
- most other VCS think of the data they store as a set of changes made to files over time
- Git thinks of data as a series of snapshots of a filesystem

## The 3 States

Git has 3 main states that files can reside in:
1. modified - a file is changed but not yet committed to the database
2. staged - a modified file in its current version is marked to go into the next commit snapshot
3. committed - the data is safely stored in the local database


