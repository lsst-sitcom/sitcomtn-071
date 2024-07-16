.. image:: https://img.shields.io/badge/sitcomtn--071-lsst.io-brightgreen.svg
   :target: https://sitcomtn-071.lsst.io/
.. image:: https://github.com/lsst-sitcom/sitcomtn-071/workflows/CI/badge.svg
   :target: https://github.com/lsst-sitcom/sitcomtn-071/actions/

################################################
StarTracker Narrow Camera to Fast Camera Offsets
################################################

SITCOMTN-071
============

There are three StarTracker cameras mounted on the Rubin Observatory TMA (Telescope Mount Assembly).  This technote describes the offsets necessary to center images in the fast camera.

**Links:**

- Publication URL: https://sitcomtn-071.lsst.io/
- Alternative editions: https://sitcomtn-071.lsst.io/v
- GitHub repository: https://github.com/lsst-sitcom/sitcomtn-071
- Build system: https://github.com/lsst-sitcom/sitcomtn-071/actions/

Build this technical note
=========================

You can clone this repository and build the technote locally if your system has Python 3.11 or later:

.. code-block:: bash

   git clone https://github.com/lsst-sitcom/sitcomtn-071
   cd sitcomtn-071
   make init
   make html

Repeat the ``make html`` command to rebuild the technote after making changes.
If you need to delete any intermediate files for a clean build, run ``make clean``.

The built technote is located at ``_build/html/index.html``.

Publishing changes to the web
=============================

This technote is published to https://sitcomtn-071.lsst.io/ whenever you push changes to the ``main`` branch on GitHub.
When you push changes to a another branch, a preview of the technote is published to https://sitcomtn-071.lsst.io/v.

Editing this technical note
===========================

The main content of this technote is in ``index.rst`` (a reStructuredText file).
Metadata and configuration is in the ``technote.toml`` file.
For guidance on creating content and information about specifying metadata and configuration, see the Documenteer documentation: https://documenteer.lsst.io/technotes.
