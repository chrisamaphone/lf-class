# Lecture 3: Higher-Order Abstract Syntax


[Code](https://github.com/chrisamaphone/lf-class/blob/main/code/stlc.elf)

## Lecture plan

* OL: Simply-typed lambda calculus (syntax and typing)
* Encoding: syntax and typing 
* LF type theory: lambda; adequacy for HOAS
* Encoding: %blocks and %worlds
* OL: Step rules (weak head reduction)
* Encoding: step rules; preserv proof

## Exercises
* Add LF encodings for product types and pairs with a "split" elimination
  form. Extend the relevant judgments and proofs. (See code file for exact
  inference rules.)
* Create an intrinsic encoding of STLC, where expression syntax is indexed
  by the type of the expression. Declare blocks and worlds for every type family.
* In class, we talked about how adequacy with HOAS depends on LF functions
  not being allowed to case-analyze their arguments. What goes wrong if we
  allow this? Construct an example, if you can.

## Further reading
* The STLC example is also [a tutorial on the Twelf
  Wiki](http://twelf.org/wiki/Proving_metatheorems:Representing_the_syntax_of_the_STLC).
* Robert Harper and Daniel Licata. [Mechanizing Metatheory in a Logical
  Framework](https://www.cs.cmu.edu/~rwh/papers/mech/jfp07.pdf) (2007).
