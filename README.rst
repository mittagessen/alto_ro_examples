Description
===========

These are 3 examples of the proposed reading order mechanism for ALTO 4.x.

Newspaper
---------

Is based off of a converted PageXML facsimile of the ONB Newseye dataset. It
shows how multiple reading orders for the same page can be encoded: one
replicating the complete order described in the original file, and a second one
grouping the text blocks into articles.

Paratext
--------

A single page of Munich Cod hebr. 117 containing both ordered (main text) and
unordered (margin notes and paratext) elements.

Margin
------

A single page of BL Add 16406 containing unordered marginalia and interlinear
corrections. The latter are encoded in a way that allows extraction of the
corrected text, i.e. the level of reading order encoding switches between whole
lines and individual words (<String>) in the lines that are corrected.
