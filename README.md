Website for the Arden2ByteCode project
======================================
Accessible here: <https://plri.github.io/arden2bytecode-homepage>

Overview
--------
This repository contains the website for Arden2ByteCode, an Arden Syntax to Java Bytecode compiler available at <http://github.com/PLRI/arden2bytecode> .   
The website is written in [Jekyll](https://github.com/jekyll/jekyll) and provides basic information about the project, associated downloads and source code repositories as well as responsible people.

The website repository has some submodules in order to include the recent GitHub [documentation wiki files](https://github.com/PLRI/arden2bytecode/wiki) of Arden2ByteCode.
The update site for the Eclipse Arden Syntax Editor feature is also imported as a submodule.

Usage
---------------
See [Using Jekyll with Pages](https://help.github.com/articles/using-jekyll-with-pages/#keeping-jekyll-up-to-date) and [Jyekyll Documentation](https://jekyllrb.com/docs/home/).

Don't forget to initialize the submodules:

    $ git clone http://github.com/PLRI/arden2bytecode-homepage.git
    $ cd arden2bytecode-homepage
    $ git submodule update --init

To update to a recent version of the repository and
all submodules use:

    $ git pull
    $ git submodule foreach git pull origin master
