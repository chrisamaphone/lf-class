# Lecture 3: Higher-Order Abstract Syntax


[Code](https://github.com/chrisamaphone/lf-class/blob/main/code/stlc.elf)

## Lecture plan

* OL: Simply-typed lambda calculus (syntax and typing)
* Encoding: syntax and typing 
* LF type theory: lambda; adequacy for HOAS
* Encoding: %blocks and %worlds
* OL: Reduction rules (weak head)
* Encoding: reduction rules; sr proof
* Encoding: add reduction under binders; update proof

## Exercises
* Add LF encodings for product types and pairs with a "split" elimination
  form. Extend the relevant judgments and proofs.
* Create an intrinsic encoding of STLC. Declare blocks and worlds for every
  type family.
* In class, we talked about how adequacy with HOAS depends on LF functions
  not being allowed to case-analyze their arguments. What goes wrong if we
  allow this? Construct an example, if you can.

## Further reading
* Robert Harper and Daniel Licata. [Mechanizing Metatheory in a Logical
  Framework](https://www.cs.cmu.edu/~rwh/papers/mech/jfp07.pdf) (2007).
