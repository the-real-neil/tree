tree
====

This is a respectful adaptation (shameless rip) of
[Steve Baker's original `tree` program][tree]. I have added autotoolery
(autoconf and automake) to Mr. Baker's original work---this should spare users
the trouble of editing the Makefile.

### build and install from source

    $ git clone https://github.com/rubicks/tree.git && \
      cd  tree                                      && \
      autoreconf -ivf .                             && \
      ./configure                                   && \
      make install

### build and install from tarball

    $ tar vxzf tree-1.7.0.tar.gz && \
      cd tree-1.7.0              && \
      ./configure                && \
      make install

### original docs

 * [CHANGES](https://raw.githubusercontent.com/rubicks/tree/master/CHANGES)
 * [INSTALL](https://raw.githubusercontent.com/rubicks/tree/master/INSTALL)
 * [README](https://raw.githubusercontent.com/rubicks/tree/master/README)


[tree]: http://mama.indstate.edu/users/ice/tree/
