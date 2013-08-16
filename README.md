# Scala School Notebooks

This is a set of lessons based on Twitter's [Scala School](https://github.com/twitter/scala_school).
covering the [Scala](http://scala-lang.org) programming language. A subset
of original lectures was converted into [IPython](http://ipython.org)'s
notebooks. Some extensions and fixes were made along the way. To run those
notebooks you need IPython 1.0+ and [IScala](https://github.com/mattpap/IScala)
backend. See IScala's documentation on how to setup your environment.

## Contents

* Basics
* Basics Continued
* Collections
* Pattern Matching
* Type Basics
* Advanced Types
* Advanced Collections

## Notes

To allow composing notebooks in a text editor, an intermediate format was
introduced (xipynb) and a simple translator to IPython's notebook format
(JSON) was implemented. The new format is defined by Markdown syntax with
GFM's triple back-quote extension that was further extended to allow delimiting
code cells. To transform `*.xipynb` to `*.ipynb` files, issue `./xipynb *`.
Note that the translator is an afternoon hack, so translation is rather naive
and you have to follow the exact syntax used in the original `*.xipynb` files
(especially when it comes to headings).

## License

Published under The Apache 2.0 License, see LICENSE.
