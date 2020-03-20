BFG Repo-Cleaner (without politics) [![Build Status](https://travis-ci.org/rtyley/bfg-repo-cleaner.svg?branch=master)](https://travis-ci.org/rtyley/bfg-repo-cleaner) ![Coverity Scan Status](https://scan.coverity.com/projects/20652/badge.svg)
================

## Why fork?

https://github.com/rtyley/bfg-repo-cleaner/issues/205

I don't care much for politics, and I really don't want to have to care because
of a stupid message that pops up whenever I use the tool. Leave American politics
out of code. (Unless you're programming a voting machine...or a nuclear reactor,
I guess...?)

[Code is a form of expression](https://github.com/rtyley/bfg-repo-cleaner/issues/205#issuecomment-285049770),
as is using the bathroom.

## Original README

_Removes large or troublesome blobs like git-filter-branch does, but faster - and written in Scala_ - [Fund the BFG](https://j.mp/fund-bfg)

```
$ bfg --strip-blobs-bigger-than 1M --replace-text banned.txt repo.git
```

The BFG is a simpler, faster ([10 - 720x](https://docs.google.com/spreadsheet/ccc?key=0AsR1d5Zpes8HdER3VGU1a3dOcmVHMmtzT2dsS2xNenc) faster)
alternative to `git-filter-branch` for cleansing bad data out of your Git repository:

* Removing **Crazy Big Files**
* Removing **Passwords, Credentials** & other **Private data**

Main documentation for The BFG is here : **https://rtyley.github.io/bfg-repo-cleaner/**
