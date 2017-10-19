STAT406 - Lecture 15 notes
================
Matias Salibian-Barrera
2017-10-19

LICENSE
-------

These notes are released under the "Creative Commons Attribution-ShareAlike 4.0 International" license. See the **human-readable version** [here](https://creativecommons.org/licenses/by-sa/4.0/) and the **real thing** [here](https://creativecommons.org/licenses/by-sa/4.0/legalcode).

Lecture slides
--------------

The lecture slides are [here](STAT406-17-lecture-15.pdf).

Nearest neighbours
------------------

Probably simplest model-free estimator for conditional class probabilities (given values for the features). *Peer-pressure*. Akin to kernel regression, also suffers from the *curse of dimensionality*. Factor or binary features need to be treated with care.

Classification Trees
--------------------

Classification trees. Instead of RSS we use a measure of (in)homogeneity of classes within leaves, partition to maximize the reduction in inhomogeneity.