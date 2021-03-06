
.. include:: ../Includes.txt



.. _introduction:

Introduction
============


.. _overview:

Overview
--------

For most people TYPO3 is equivalent to a CMS providing a backend for
management of the content and a frontend engine for website display.
However TYPO3s core is natively designed to be a general purpose
framework for management of database content. The core of TYPO3 CMS
delivers a set of principles for storage of this content, user access
management, editing of the content, uploading and managing files etc.
Many of these principles are expressed as an API (Application
Programmers Interface) for use in *extensions* which ultimately
add most of the real functionality.

.. figure:: ../Images/Typo3CmsStructure.png
   :alt: The TYPO3 CMS code architecture


So the  *core* is the skeleton and  *extensions* are the muscles,
fibers and skin making a full bodied CMS. In this document I cut to
the bone and provide a detailed look at the core of TYPO3 CMS including
the API available to the outside. This is supposed to be the final
technical reference apart from source code itself which is - of course
- the ultimate documentation.

This manual is a complement to :ref:`Core APIs <t3api:start>`.


.. _audience:

Intended audience
-----------------

This document is intended to be a reference for experienced TYPO3 CMS
developers. For intermediates it will help you to become experienced!
But the document presumes that you are well familiar with TYPO3 and
the concepts herein. Further it will presume knowledge in the
technical end; PHP, MySQL, Unix etc.

The goal is to take you "under the hood" of TYPO3 CMS. To make the
principles and opportunities clear and less mysterious. To educate you
to help continue the development of TYPO3 along the already
established lines so we will have a consistent CMS application in a
future as well.And hopefully my teaching on the deep technical level
will enable you to educate others higher up in the "hierarchy". Please
consider that as well!


.. _what-s-new:

What's new
^^^^^^^^^^

This version is updated for TYPO3 CMS 7.

*(currently being edited)*


.. _feedback:

Feedback
^^^^^^^^

For general questions about the documentation get in touch by writing
to `documentation@typo3.org <mailto:documentation@typo3.org>`_ .

If you find a bug in this manual, please be so kind as to check the
online version on http://docs.typo3.org/typo3cms/InsideTypo3Reference/.
From there you can hit the "Edit me on GitHub" button in the top right corner
and submit a pull request via GitHub. Alternatively you can just file an issue
using the bug tracker: https://github.com/TYPO3-Documentation/TYPO3CMS-Reference-Typoscript/issues.

Maintaining high quality documentation requires time and effort
and the TYPO3 Documentation Team always appreciates support.
If you want to support us, please join the documentation
mailing list/forum (http://forum.typo3.org/index.php/f/44/).


.. _credits:

Credits
-------

This manual was originally written by Kasper Skårhøj. It was further
maintained, refreshed and expanded by François Suter.
