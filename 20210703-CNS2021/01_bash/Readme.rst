Effective use of Bash
---------------------

- Instructor: @kernfel

Abstract
~~~~~~~~
The purpose of this tutorial is to introduce participants to the tools they need in order to comfortably and confidently work with a Unix/Linux command line terminal. Unlike graphical user interfaces, which are often self-explanatory or have obvious built-in help options, the purely text-based nature of a command line terminal can be intimidating and confusing to novice users. Yet, once mastered, the command line offers more flexibility and smoother workflows for many tasks, while being entirely irreplaceable for things such as cluster access.

In this tutorial, we aim to introduce participants to the concepts and tools they need to confidently operate within a Unix/Linux command line environment. In particular, the tutorial is developed for Bash (as per the title), which should cover most Linux and MacOS* use cases. We hope to provide participants with a firm understanding of the basics of using a shell, as well as an understanding of the advantages of working from a command line.

The tutorial is aimed not only at novices who have rarely or never used a command line, but also at occasional or even regular users of bash who seek to expand or refresh their repertoire of everyday commands and the kinds of quality-of-life tricks and shortcuts that are rarely covered on StackExchange questions.

*) While MacOS has switched from bash to zsh as its default shell, zsh's operation is sufficiently similar for the purposes of this tutorial.

Prerequisites
~~~~~~~~~~~~~
A working copy of bash; participants on Linux and MacOS are all set.
Participants on Windows have several options to get hold of a bash environment without leaving familiar territory:
* Install `Git for Windows <https://gitforwindows.org/>`_, which includes a Git Bash emulation with most of the standard tools you might expect in a Linux/Unix environment, plus of course Git.
* Alternatively, `enable WSL2 <https://docs.microsoft.com/en-us/windows/wsl/install-win10#install-the-windows-subsystem-for-linux>`_ and `install Ubuntu <https://www.microsoft.com/en-gb/p/ubuntu/9nblggh4msv6>`_ as a virtual machine hosted by Windows. Somewhat ironically, this requires at least one use of a command line terminal (though not bash); on the upside, the Linux-on-Windows experience is a smooth and safe first step into Linux territory.

Topics
~~~~~~
* Basics to refer back to: Operating your bash shell (with key bindings and patience)
* The grammar of a shell command line
* Getting around: Navigating within and beyond your computer (~, pwd, cd, pushd/popd, ssh)
* Seeing what's there: ls, globbing, and strategies for naming your files
* File system manipulations (mv, cp/scp, rm, mkdir, rmdir, ln -s, touch)
* Looking into files (cat, head & tail, more or less, grep, diff, sort)
* Putting things together: Piping and redirection
* What to do when stuck: Man, I need some help here.
