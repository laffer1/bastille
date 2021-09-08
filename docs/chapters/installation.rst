Installation
============
Bastille is available in the official FreeBSD ports tree at
`sysutils/bastille`. Binary packages available in `quarterly` and `latest`
repositories.

Current version is `0.9.20210714`.

To install from the FreeBSD package repository:

* quarterly repository may be older version
* latest repository will match recent ports


PKG
---

.. code-block:: shell

  pkg install bastille


To install from source on FreeBSD (don't worry, no compiling):

ports
-----

.. code-block:: shell

  make -C /usr/ports/sysutils/bastille install clean

To install from the MidnightBSD package repository:

mport
---

.. code-block:: shell

  mport install bastille

To install from source on MidnightBSD:

mports
---

.. code-block:: shell

  make -C /usr/mports/sysutils/bastille install clean

GIT
---

.. code-block:: shell

  git clone https://github.com/BastilleBSD/bastille.git
  cd bastille
  make install

This method will install the latest files from GitHub directly onto your
system. It is verbose about the files it installs (for later removal), and also
has a `make uninstall` target.
