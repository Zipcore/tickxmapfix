tickxmapfix
===========

This is a SourceMod plugin, it improves maps which are made only for tick 66 servers to work better on servers with a differnt tickrate

Merging smlib updates
================
To update smlib: We will merge the latest smlib/feature-pluginmanager into addons/sourcemod.
Commit messages are squashed, that means the history of feature-pluginmanager is compressed to one commit.
```
git remote add smlib git@github.com:bcserv/smlib.git
// folder addons/sourcemod must exist!
git merge --squash -srecursive -Xsubtree=addons/sourcemod --strategy-option theirs  smlib/feature-pluginmanager
```
