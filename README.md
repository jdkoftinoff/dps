David's Docbook Publishing System
=================================

A Java shell environment for publishing Docbook 5 to multiple output formats.

Pre-Requisites
--------------

All platforms require: 

  - Java

Windows users must install XMLShell

  1. Browse to [XMLSH](http://sourceforge.net/projects/xmlsh/ XMLSH)
  
  2. Download the package appropriate for your OS.
  
  3. Expand the package into `*this directory*\opt\xmlsh_1_1_4`
  
On OS X and Linux clients, DPS will attempt to automatically download and install XMLSH into `opt`.

Installation
------------

DPS attempts to be self-installing, downloading the packages it needs from their repositories.

Examine `sbin/kickstart` if packages fail to install.

Booting
-------

Windows:

  1. At a command prompt in this directory, type `boot` and press `enter`.
  
  2. At the `dps$` prompt, type `dhelp` for help.


Posix (OS X, Linux):
  
  1. At a Bash command prompt in this directory, type `./boot` and press `enter`.
  
  2. At the `dps$` prompt, type `dhelp` for help.