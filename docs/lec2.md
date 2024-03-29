# Lecture 2: LF Type Theory


[Code](https://github.com/chrisamaphone/lf-class/blob/main/code/data.elf)

## Lecture plan

* LF type theory (minus lambda)
* Datatype encodings and (informal) adequacy

## Exercises
* Come up with a second proof that `(node (node leaf leaf) (node leaf leaf))`
  is balanced.
* Come up with both an extrinsic and intrinsic encoding for AVL trees. Show
  that the extrinsic encoding is not adequate, and that the intrinsic one
  is.
* Exercise (bonus): can you describe a type theory that "stratifies" the
  levels of [syntax, judgments, theorems], all of which LF uses dependent
  functions to represent? What would the advantages/disadvantages be?

## Further reading
* [A Framework for Defining
  Logics](https://homepages.inf.ed.ac.uk/gdp/publications/Framework_Def_Log.pdf),
  Harper, Honsell, and Plotkin. The original LF paper.
* [Computation and Deduction](https://cs.mcgill.ca/~bpientka/courses/comp523-08/cd.pdf) Chapter 3 (Formalization in a Logical Framework)
* [Church and Curry: Combining Intrinsic and Extrinsic
  Typing](https://www.cs.cmu.edu/~fp/papers/andrews08.pdf), by Frank
  Pfenning
