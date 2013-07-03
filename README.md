pyinter  [![Build Status](https://travis-ci.org/intiocean/pyinter.png)](https://travis-ci.org/intiocean/pyinter)
=======

The what?
---------
An interval package for Python which deals with interval arithmetic and sets of intervals *(discontinuous ranges)*. **It is currently in developement and not yet fully code complete or fully tested.**

The how?
--------
I Started development of this library on a weekend. Initially, I have just implemented features which I wanted to use and a couple of others which it felt natural to include.

The why?
--------
*Warning: the following may or may not be rather geeky, you have been warned!* The inital reason I started developement of an interval package in python was that I couldn't find one which dealt with open and closed intervals and I needed one to play around with some ideas I was having regarding dependency resolution of python packages.

The help
--------
Documentation is available here: http://pyinter.readthedocs.org

Done
----
- interval objects which can be
    - unioned
    - intersected
    - easily constructed using helper functions: *open, closed, openclosed and closedopen*
- interval sets which can be
    - unioned
    - intersected
- tests on interval
    - construction
    - comparison
    - intersection and union
- tests on interval set
    - construction
    - comparison
    - intersection and union
- sphinx documentation available here: http://pyinter.readthedocs.org
- continous integration on travis ci: https://travis-ci.org/intiocean/pyinter
- Example use: daterange

Todos
-----
- How to install
- add to pypi
- look for enhancements to the code (timing, optimisation, tidying of interval_set ...)
- make the project a homepage
- check pylint
- Create some concrete example use cases (version range)
- ensure all functions have docstrings describing the inputs and outputs
- make sure there are no tabs! (whops)
- add a build for python 3.3 to travis ci and get it passing (there is some kind of import error)
