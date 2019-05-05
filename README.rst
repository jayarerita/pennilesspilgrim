================
pennilesspilgrim
================

Below is a summary of the puzzle taken form the NYTimes...
***********************************************************
Credit: The NYTimes' Daniel Finkel
https://wordplay.blogs.nytimes.com/2013/08/26/pilgrim/

A pilgrim arrives in Duona, a sixteen-block town created by five 
streets running north-south that intersect with five streets running
east-west. Like all pilgrims, she arrives in the northwest corner of 
town, and needs to make her way to a shrine in the southeast corner. 
Unfortunately for the pilgrim, Duona imposes a tax system on visitors, 
charging 2 silver pieces for each block walked to the east, and 
doubling what you owe every time you walk south. To make the payment 
system fairer and encourage longer stays, they subtract 2 silver pieces 
for each block walked to the west, and halve what you owe when you walk
a block north. The townsfolk keep track of your path, and you must pay 
in full on your arrival in the southeast corner. (Legend has it that certain 
savvy travelers have planned trips through the town and ended up receiving 
silver by following the tax rules.) As a central tenant of her pilgrimage 
she cannot travel the same stretch of ground twice.

The pilgrim has no money, and has no intention of leaving with any. 
How can she travel to the southeast corner of Duona without owing or 
receiving any silver?
************************************************************

This package allows a user to play interactively or to run various algorithms or solving
methods against it. 

Summary of directions:
North: x / 2
South: x * 2
East: x + 2
West: x - 2

The grid of streets is set up as a (0, 1, 2, 3, 4) x (0, 1, 2, 3, 4) grid of 
coordinates representing corners (intersections of streets where the coordinate 
(0, 0) is the bottom left (South East) corner.

['(04)', '(14)', '(24)', '(34)', '(44)']
['(03)', '(13)', '(23)', '(33)', '(43)']
['(02)', '(12)', '(22)', '(32)', '(42)']
['(01)', '(11)', '(21)', '(31)', '(41)']  N↑
['(00)', '(10)', '(20)', '(30)', '(40)']  E→


.. image:: https://img.shields.io/pypi/v/pennilesspilgrim.svg
        :target: https://pypi.python.org/pypi/pennilesspilgrim

.. image:: https://img.shields.io/travis/jayarerita/pennilesspilgrim.svg
        :target: https://travis-ci.org/jayarerita/pennilesspilgrim

.. image:: https://readthedocs.org/projects/pennilesspilgrim/badge/?version=latest
        :target: https://pennilesspilgrim.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status




Package to implement versions of the Penniless Piglrim math puzzle by Daniel Finkel


* Free software: MIT license
* Documentation: https://pennilesspilgrim.readthedocs.io.


Features
--------

* TODO

Credits
-------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
