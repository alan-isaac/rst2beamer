History
=======


v0.9.2
-------------------------------------

* Incorporate all rst2beamer.py changes from f-i.
* Fix use-latex-citations (broken by change in docutils latex writer)
* Remove BeamerTranslator.visit_docinfo_item and rely on
  LaTeXTranslator.visit_docinfo_item
  Remark: the corresponding test is now out of date
* change PreambleCmds.documenttitle to use institute instead of author
  in order to get easy support for multiple authors
  (with minimum change from LaTeXTranslator).
  To match font, date is now forced to small.

v0.9.1, 2016-01-11
------------------

* Separate names in author list with commas for use in ``shortauthor``.


v0.9, 2015-03-27
----------------

* Use better defaults. The default theme is now ``Ilmenau`` and the
  ``--overlaybullets`` is now disabled by default.


v0.8.5, 2015-03-07
------------------

* Respect ``--language`` in the context of admonition directives.


v0.8.4, 2014-11-14
------------------

* Fix width calculation in columns.


v0.8.3, 2014-08-26
------------------

* Improve scaling.


v0.8.2, 2013-12-01
------------------

* Enable syntax highlighting by default.


v0.8, 2013-06-04
----------------

* Added Python 3 support.


v0.6.6, 2009-11-06
------------------

* Added experimental support for codeblocks, which may be syntax-colored with
  Pygments.

* Normalised all directive names to ``beamer-`` (as opposed to ``r2b_``) in
  line with general docutils style, although the old names are still silently
  supported.


v0.6.4, 2009-10-22
------------------

* The parsed-literal environment was losing indentation, and perhaps has been
  since docutils 0.4. It now works correctly.

* Added "calling" information to examples. Also added bullet example.


v0.6.2, 2009-10-20
------------------

* It seems there have been some changes in the docutils LaTeX2e writer, which
  the Beamer writer is based upon. Hopefully they've all been caught.

* Corrected url in header of source, as well as some misspellings.


v0.6.1, 2009-09-14
------------------

* Added note environment

* Added manual


v0.6, 2009-09-03
----------------

* Introduced column environment


v0.5.3, 2009-07-16
------------------

* Fixed manifest so source included (facepalm)

* Changed setup.py to get single-file module to install


v0.5.1, 2009-05-08
------------------

* Expanded documentation.


v0.5, 2009-05-07
----------------

* Shift to setuptools distribution with script installation.


v0.3, 2009-03-25
----------------

* RK takes over. Sections and subsections are supported. Images default to
  being centered and having a height of 0.7\textheight.


v0.2.1, 2008-08-30
------------------

* Date approximate. Earlier versions of rst2beamer did not work with docutils
  0.4, seemingly due to changes in the LaTeX writer.


v0.2.0, 2007-08-30
------------------

* Date approximate. Initial release.
