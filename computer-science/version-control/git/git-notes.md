# Git/GitHub Notes

## What is Git?

Git is a version control system that records changes to files so that you can see and work with version history

This allows for
- reverson of files back to a previous state
- reversion of the entire project back to a previous state
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

Git therefore has 3 main sections in any project:
1. the working tree - a single checkout of one version of the project
2. the staging area - a file that stores info about what goes into the next commit
3. the Git directory (repository) - where Git stores metadata and the database for the project

The basic Git workflow:
1. you modify files in your working tree
2. you stage the changes you want committed
3. you commit them which makes them a part of the repo

## Installation

Linux
```
$ sudo apt install git-all
```
MacOS
```
$ git --version
```
Windows

Git website

## First-Time Git Setup
