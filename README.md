Git Sweep
=========

Git Sweep is a command line tool for cleaning up stale local branches in a Git repository. Git Sweep finds all local branches that don't have an associated remote, and deletes them if approved.

Installation
------------

```shell
brew install edahlseng/core/git-sweep
```

_Optional:_

It's recommended to add an alias to your Git config:

```
[alias]
	sweep = git-sweep
```

Usage
-----

Inside of a Git repository, run `git sweep` and follow the prompts. (Note: If a Git alias was _not_ created during installation, then `git-sweep` will need to be run instead.)
