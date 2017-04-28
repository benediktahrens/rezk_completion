Rezk Completion
===============

This Coq library mechanizes the Rezk completion as described in
http://arxiv.org/abs/1303.0584

It builds upon V. Voevodsky's Foundations library, available on
http://arxiv.org/abs/1401.0053

**Attention:** This repository does not receive any updates. Its contents have been fully integrated into https://github.com/UniMath/UniMath.

# Installation

This library is part of the UniMath repository, available at https://github.com/UniMath/UniMath . 
The recommended way to obtain this library is to install UniMath. Instructions for installing UniMath can be found on the UniMath web page.
The below installation instructions should be considered as obsolete.


## Requirements

### Coq

The library compiles under Coq8.3pl5, patched according to the instructions given in 
http://arxiv.org/abs/1401.0053. 
Lower patch levels of Coq8.3, e.g., Coq8.3pl2, are likely to work as well.

### Libraries

Files used from V. Voevodsky's Foundations:

  - uuu.v
  - uu0.v
  - hProp.v
  - hSet.v
  - funextfun.v

They should be installed in the user-contrib/Foundations directory of Coq, so
Coq can find them. 


Licensing and copyright
=======================

Authors: Benedikt Ahrens, Chris Kapulkin, Mike Shulman

The code in this repository is made available under the terms of "CC0
1.0 Universal", see
[http://creativecommons.org/publicdomain/zero/1.0/legalcode](http://creativecommons.org/publicdomain/zero/1.0/legalcode).
That means, basically, that we disclaim all rights, including copyright, and put
it into the public domain.

The code in this repository is (also) put into the public domain, which
means we disclaim any and all copyright protection.

