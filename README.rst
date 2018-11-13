ITKRobustPredicate
==================

.. |CircleCI| image:: https://circleci.com/gh/InsightSoftwareConsortium/ITKRobustPredicate.svg?style=shield
    :target: https://circleci.com/gh/InsightSoftwareConsortium/ITKRobustPredicate

=========== =
   Linux
=========== =
|CircleCI|
=========== =


Overview
--------

`ITK <http://itk.org>`_ wrapper for the third party library `ITKSKEWCHUK` for
adaptive precision floating-point arithmetic and fast robust geometric
predicates.

A more detailed description can be found in the article::

  Jonathan Richard Schewchuk:
  Adaptive Precision Floating-Point Arithmetic and Fast Robust Geometric
  Predicates,
  Discrete & Computational Geometry, vol. 18(3), 305-363 1997

For more information refer to::

  http://www.cs.cmu.edu/~quake/robust.html


This module is available in the ITK source tree as a Remote module. To enable
it, set::

  Module_RobustPredicate:BOOL=ON

in ITK's CMake build configuration.


License
-------

This software is distributed under the Apache 2.0 license. Please see
the *LICENSE* file for details.


Acknowledgements
----------------

Stéphane Rigaud, Bertrand Moreau, and Alexandre Gouaillard contributed to this
module.
