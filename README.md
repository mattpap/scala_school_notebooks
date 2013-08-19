# Scala School Notebooks

This is a set of lessons based on Twitter's [Scala School](https://github.com/twitter/scala_school)
covering the [Scala](http://scala-lang.org) programming language. A subset
of original lectures was converted into [IPython](http://ipython.org)'s
notebooks. Some extensions and fixes were made along the way. To run those
notebooks you need IPython 1.0+ and [IScala](https://github.com/mattpap/IScala)
backend. See IScala's documentation on how to setup your environment.

[**Start here**](http://mattpap.github.io/scala_school_notebooks/index.html)

## Contents

* [Basics](http://mattpap.github.io/scala_school_notebooks/Basics.html) &mdash; Values, functions, classes, methods, inheritance, try-catch-finally. Expression-oriented programming [(download)](http://mattpap.github.io/scala_school_notebooks/Basics.ipynb)
* [Basics Continued](http://mattpap.github.io/scala_school_notebooks/Basics Continued.html) &mdash; Case classes, objects, packages, apply, update, Functions are Objects (uniform access principle), pattern matching [(download)](http://mattpap.github.io/scala_school_notebooks/Basics Continued.ipynb)
* [Collections](http://mattpap.github.io/scala_school_notebooks/Collections.html) &mdash; Lists, Maps, functional combinators (map, foreach, filter, zip, folds) [(download)](http://mattpap.github.io/scala_school_notebooks/Collections.ipynb)
* [Pattern Matching & Functional Composition](http://mattpap.github.io/scala_school_notebooks/Pattern Matching.html) &mdash; More functions! PartialFunctions, more Pattern Matching [(download)](http://mattpap.github.io/scala_school_notebooks/Pattern Matching.ipynb)
* [Type & Polymorphism Basics](http://mattpap.github.io/scala_school_notebooks/Type Basics) &mdash; Basic Types and type polymorphism, type inference, variance, bounds, quantification [(download)](http://mattpap.github.io/scala_school_notebooks/Type Basics.ipynb)
* [Advanced Types](http://mattpap.github.io/scala_school_notebooks/Advanced Types.html) &mdash; Advanced Types, view bounds, higher-kinded types, recursive types, structural types [(download)](http://mattpap.github.io/scala_school_notebooks/Advanced Types.ipynb)
* [More Collections](http://mattpap.github.io/scala_school_notebooks/Advanced Collections.html) &mdash; Tour of the Scala Collections library [(download)](http://mattpap.github.io/scala_school_notebooks/Advanced Collections.ipynb)

## Notes

To allow composing notebooks in a text editor, an intermediate format was
introduced (xipynb) and a simple translator to IPython's notebook format
(JSON) was implemented. The new format is defined by Markdown syntax with
GFM's triple back-quote extension that was further extended to allow delimiting
code cells. To transform `*.xipynb` to `*.ipynb` files, issue `./xipynb`. This
will also generate corresponding `*.html` files using `ipython nbconvert`.
Note that the translator is an afternoon hack, so translation is rather naive
and you have to follow the exact syntax used in the original `*.xipynb` files
(especially when it comes to headings).

## License

Published under The Apache 2.0 License, see LICENSE.
