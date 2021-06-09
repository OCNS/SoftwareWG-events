Effective use of Git
---------------------

- Instructor(s): Ankur Sinha (@sanjayankur31)

Abstract
~~~~~~~~~

Version control is a necessary skill that users writing any amount of code should possess.
Git is a popular version control tool that is used ubiquitously in software development.

This hands-on session is aimed at beginners who have little or no experience with version control systems and Git.
It will introduce the basics of version control and walk through a common daily Git workflow before moving on to show how Git is used for collaborative development on popular Git forges such as GitHub.
Finally, it will show some advanced features of Git that aid in debugging code errors.

Prerequisites
~~~~~~~~~~~~~~~

The session is intended to be a hands-on session, so all attendees will be expected to run Git commands.
A working installation of Git is, therefore, required for this session.
We will use GitHub as our Git remote for forking and pull/merge requests.
So a GitHub account will also be required.

- Linux users can generally install Git from their default package manager:
  Fedora: ``sudo dnf install git``
  Ubuntu: ``sudo apt-get install git``
- Windows users should use `Git for Windows <https://gitforwindows.org/>`__.
- MacOS users should use ``brew`` to install ``git``: ``brew install git``.

More information on installing Git can be found on the project website: https://git-scm.com/

Topics
~~~~~~

- a brief introduction to Git
  - references, options
  - where to get help

- using Git on a daily basis:
  - creating a new repository (``init``)
  - adding files and staging files (``add, add -i``)
  - ignoring files (``.gitingore``)
  - stashing (``stash``)
  - viewing changes (``diff, log``)
  - committing files (``commit``)
  - using branches to organise the development workflow (``branch, checkout``)
  - tagging (``tag``)
  - creating an archive (``archive``)

- using Git for collaborative development
  - remotes, forks (``remote``)
  - pushing and pulling (``push, pull``)
  - pull requests and merging (``merge``)
  - merge conflicts and resolving them

- slightly advanced git
  - Git worktrees (``worktree``)
  - interactive rebasing (``rebase -i``)
  - cherry-picking (``cherry-pick``)
  - debugging with git-bisect (``bisect``)
