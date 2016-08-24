Apache Hadoop basic monitoring setup
====================================

Apache-Hadoop-Watcher 
---------------------

Version 0.01

This is a set of scripts meant for Apache Hadoop runtime
metrics collection and monitoring. This monitors Hadoop 
configuration along with runtime monitoring via JMX and
Yarn health monitoring.


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

- Data::Dumper;
- IO::Socket::INET;
- JSON;
- LWP::UserAgent;
- XML::Twig;

See Also:
---------
Available in cpan as a package at http://search.cpan.org/~snehasis/Apache-Hadoop-Watcher-0.01/

Copyright and Licence:
----------------------
Copyright (C) 2015 by Snehasis Sinha
Apache Licence 2.0
