Semester Project Marius Furter - Spring 2021


# Meetings


## [[2021-05-04]]



## [[2021-04-06]]

- Birkhoff representation theory for distributed lattices - every distributive lattice is isomorphic to the lattice of upper sets on some poset.

- was working with Shalk - da Paiva, poset-valued sets

- for next time: examples with interpretations

## [[2021-03-30]]

- Paper by Yetter
  - Quantale with a duality is the pre-order version of a *-autonomous category

- Marsden paper
  - Quantitative resource theories, look at quantale enriched profunctors
  - Free categories based on rules that one wants to allow
  - notion of an internal monad describing closure operation (getting from an arbitrary set of feasible things to a profunctor)

- Ref: poset-valued sets, how to build models for linear logic

- Planning next steps
  - look at the special case where V = Q = Bool
  - look at the case where V = Q is any commutative unital quantale
  - look at the case where V \neq Q = Bool.
  - throughout: let's try to spell out examples and keep an eye on applications and interpretation. In the end of the day, we want some sort of 'linear logic way' to reason in the context of design problems.

## [[2021-03-23]]

Series of blog posts by [[Simon Willerton]] on the n-cafe:
- [The nucleus of a profunctor: some categorified linear algebra](https://golem.ph.utexas.edu/category/2013/08/the_nucleus_of_a_profunctor_so.html)
- [Formal concept analysis](  https://golem.ph.utexas.edu/category/2013/09/formal_concept_analysis.html)
- [Classical dualities and formal concepts analysis](https://golem.ph.utexas.edu/category/2013/09/classical_dualities_and_formal.html)
- [Galois correspondences and enriched adjunctions](https://golem.ph.utexas.edu/category/2014/02/galois_correspondences_and_enr.html)
- [Fuzzy logic and enriching over [0,1]](https://golem.ph.utexas.edu/category/2014/03/fuzzy_logic_and_enriching_over.html)  


## [[2021-03-16]]

 coherence spaces, three element poset linearly ordered (no, maybe,  yes)

  - (co)presheaves -> look into

## [[2021-03-09]]
  - 3 ideas of where to put the linear logic in the boolean profunctor picture
   -  put "in" the preorders, freely generate a linera logic picture in some sense
     - restricts class of preorders...
     - ![[Screen Shot 2021-03-09 at 15.56.12.png]]
   - linear logic structure in the category where one is putting the feasibility relations
     - i.e. relate R --> F to implication in linear logic
       - Boolean is compact closed, so linear logic already, but it is degenerate b/c compact closed (connectives coincide)
         - can one undifferentiate

   - look at possible linear logic structure on the internal arrows part from profunctors
     - replace Bool with a more interesting preorder structure and equip it with linear logic operations?
       - true / maybe / false ?
   - looking at the queries


 Reference: poset-valued sets
