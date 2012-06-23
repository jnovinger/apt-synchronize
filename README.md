apt-synchronize
===============

## Use case
Christopher has two development machines he'd like to keep in sync, with respect to [Debian's](http://www.debian.org) ``apt`` tool.

## ``apt-synchronize``

``apt-synchronize`` is a tool that will, either invoked manually or from a tool like ``cron``, update the list of locally installed Debian packages, add it to the Git repo, and then sync with a remote. On the other end, ``apt-synchronize`` will facilitate the installation of packages that were installed on the original machine.

### How to use ``apt-synchronize``

Coming soon!

### Timeline

* v 0.1 - Implement 'install' syncronization
* v 0.2 - Implement 'remove' syncronization
