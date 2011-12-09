========================
standard documents tools
========================

This package wants to collect small scripts and tools that help to author, read, convert or process standard documents from standardization bodies like IETF (RFC), W3C, OASIS and others.

Please help ( TODO_ ) to make this a useful collection!

Tools included:

* rfc-index-xml2bibtex: build bibtex database from IETF's rfc-index.xml file.
* w3c-rfc-to-bibtex

References and Bibtex
=====================

The Collection of `Computer Science Bibliographies`_ has millions of references and pointers to tools and stuff.

.. _Computer Science Bibliographies: http://liinwww.ira.uka.de/bibliography

IETF (RFC)
----------

draft-carpenter-rfc-citation-recs-01_ provides recommendations for the Bibtex entries.

.. _draft-carpenter-rfc-citation-recs-01: https://datatracker.ietf.org/doc/draft-carpenter-rfc-citation-recs

TODO
====

* Is standard documents tools a good name?

* List of standardization bodies:

  * `Object Management Group <http://www.omg.org>`_
  * `International Organization for Standardization (ISO) <http://www.iso.org>`_
  * `International Electrotechnical Commission (IEC) <http://www.iec.ch>`_
  * `International Telecommunication Union (ITU) <http://www.itu.int>`_
  * `Internet Engineering Task Force (IETF) <http://www.ietf.org>`_
  * `Internet Society (ISOC) <http://www.isoc.org>`_
  * `World Wide Web Consortium (W3C) <http://www.w3c.org>`_
  * `Organization for the Advancement of Structured Information Standards (OASIS) <http://www.oasis-open.org>`_
  * `Free Standards Group <http://www.freestandards.org>`_
  * `IEEE Standards Association <http://standards.ieee.org>`_
  * more infos: http://en.wikibooks.org/wiki/FOSS_Open_Standards/Standard-Setting_and_Open_Standards

* package rfc authoring tools, if sbd. wants to have them:

  * www.rfc-editor.org/rfc-editor/tools_81.pdf
  * http://aaa-sec.com/nroffedit
  * http://xml.resource.org
  * http://tools.ietf.org/
  * http://www.ietf.org/tools/

* find and package tools to convert standard documents to other formats, that
  are nicer to read or print.

  * http://users.erols.com/blilly/formatting/index.html

* Bibtex entries for W3C: http://webcapita.com/w3cbib/by-year

* Debian wishlist issues:

  * build Bibtex entries for RFC documents (Closes: #648205)
  * rfc command to quickly open a rfc document given a number or keyword
    (Closes: #296635, #116567, #272826, #31383, #74385)
  * Recommend available rfc readers: emacs-goodies-el and qrfcview
  * This package could also become a build-dependency for doc-ref and include
    some of the scripts to download and process data from rfc-editor.org
