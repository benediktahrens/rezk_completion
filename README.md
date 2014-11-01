Rezk Completion
===============

This Coq library mechanizes the Rezk completion as described in
http://arxiv.org/abs/1303.0584

It builds upon V. Voevodsky's Foundations library, available on
http://arxiv.org/abs/1401.0053

The files contain the formalization of the Rezk Completion:

* *precategories.v*
  * precategories
  * isomorphisms in precategories
* *functors_transformations.v*
  * functors and natural transformations
  * various properties of functors
  * the functor precategory is a category if the target category is
* *sub_precategories.v*
  * sub-precategories
  * image factorization of a functor
  * a full subprecategory of a category is a category
* *equivalences.v*
  * definition of adjunction
  * adjoint equivalence of precategories
  * proof that an adjoint equivalence of categories yields a weak equivalence of objects
  * a fully faithful and essentially surjective functor induces equivalence of precategories if its source is a category
* *category_hset.v*
  * definition of the precategory of sets
  * proof that it is a category
* *yoneda.v*
  * definition of Yoneda embedding
  * proof that it is fully faithful
* *whiskering.v*
  * definition of whiskering
* *precomp_fully_faithful.v*
  * precomposition with a fully faithful and essentially surjective functor yields a fully faithful functor
* *precomp_ess_surj.v*
  * precomposition with a fully faithful and essentially surjective functor yields an essentially surjective functor
* *rezk_completion.v*
  * put the previous files together and exhibit the Rezk completion


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

