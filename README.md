Apache Hadoop basic monitoring setup
====================================

Apache-Hadoop-Watcher 
---------------------

Version 0.01

The README is used to introduce the module and provide instructions on
how to install the module, any machine dependencies it may have (for
example C compilers and installed libraries) and any other information
that should be provided before the module is installed.

A README file is required for CPAN modules since CPAN extracts the
README file from a module distribution so that people browsing the
archive can use it get an idea of the modules uses. It is usually a
good idea to provide version information here so that people can
decide whether fixes for the module are worth downloading.

Installation:
-------------

To install this module type the following:
```
   perl Makefile.PL
   make
   make test
   make install
```

Dependencies:
-------------

This module requires these other modules and libraries:

Data::Dumper;
IO::Socket::INET;
JSON;
LWP::UserAgent;
XML::Twig;

See Also:
---------
Available in cpan as a package at http://search.cpan.org/~snehasis/Apache-Hadoop-Watcher-0.01/

Copyright and Licence:
----------------------
Copyright (C) 2015 by Snehasis Sinha
Apache Licence 2.0
