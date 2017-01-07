pstats2
=======

.. image:: https://travis-ci.org/johnsonc/pstats2.png?branch=master
   :alt: Build status
   :target: https://travis-ci.org/johnsonc/pstats2

*pstats2* is *pstats* module fork


It's compatible with:

* Python 2.7
* CPython 2.x >= 2.6, 3.x >= 3.2
* PyPy 1.9+

This fork is compatible with Python 2.7 (without CPython) on Ubuntu 14.04. 
Unicode errors in the main pip library and in python3 specfic code in jstasiak's master were the reason for this version.


It's API-compatible with *pstats*. Changes between *pstats* and *pstats2*:

* ability to sort by time per call (``percall``) and cumulative time per call (``cumpercall``)

Copyright
---------

Changes in this fork (c) Johnson Chetty, 2017. Authors of original module are listed in ``pstats2.py``.

This source code is licensed under Apache License, Version 2.0. See LICENSE file for details.
