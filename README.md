apt-cyg
=======

 Credits:
 - [John Peterson](https://github.com/john-peterson): Fork of [apt-cyg](https://github.com/john-peterson/apt-cyg) from https://github.com/john-peterson/apt-cyg
 - Google Code: Fork of [apt-cyg](http://code.google.com/p/apt-cyg/) from http://code.google.com/p/apt-cyg/

Intro
-----
apt-cyg is a command-line installer for Cygwin which cooperates with Cygwin Setup and uses the same repository. The syntax is similar to apt-get. Usage examples:

* "apt-cyg install <package names>" to install packages
* "apt-cyg remove <package names>" to remove packages
* "apt-cyg update" to update setup.ini
* "apt-cyg show" to show installed packages
* "apt-cyg find <pattern(s)>" to find packages matching patterns
* "apt-cyg search <patterns>" to find packages matching patterns (alias of find)
* "apt-cyg describe <pattern(s)>" to describe packages matching patterns
* "apt-cyg packageof <commands or files>" to locate parent packages

Quick start
-----------
First install curl and wget through the standard cygwin setup program. Then run the following commands:

    # curl -o /usr/bin/apt-cyg https://raw.github.com/sachingaikwad123/apt-cyg/master/apt-cyg
    # chmod +x /usr/bin/apt-cyg

use apt-cyg, for example:

    # apt-cyg install nano
