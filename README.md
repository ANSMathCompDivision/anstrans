ANS Transactions LaTeX / LyX Templates
======================================

The ANS transactions template is a LaTeX/LyX template for the American Nuclear
Society's transactions. The "official" template lives as a snapshot of this
repository at
[the ANS Transactions site](http://www.ans.org/pubs/transactions/).

The template is based on the `anstrans.cls` class file which can be used
directly with LaTeX (see `example.tex`) or through the anstrans.layout LyX file
(see `./lyx` subdirectory).  The template also includes an `ans.bst`
bibliography style file that conforms to ANS style guidance.

LaTeX
-----

To compile the example (including the bibliography), execute:

    pdflatex example
    bibtex example
    pdflatex example
    pdflatex example

LyX
---

It is recommended that users begin with the `lyx/example.lyx` file, replace
placeholder information, and view it using LyX's built-in view mechansim.  The
multiple compilation steps (including the bibliography) described above will be
performed automatically.
