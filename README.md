apt-cyg
=======

Fork of [apt-cyg](http://code.google.com/p/apt-cyg/) from Google Code

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
First install wget through the standard cygwin setup program. Then run the following commands:

    # wget -O/usr/bin/apt-cyg https://raw.github.com/cfg/apt-cyg/master/apt-cyg; chmod +x /usr/bin/apt-cyg

use apt-cyg, for example:

    # apt-cyg install nano
