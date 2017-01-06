.. image:: https://gitcdn.xyz/repo/LuisAlejandro/doctorhastie/master/docs/_static/title.svg

-----

.. image:: https://img.shields.io/pypi/v/doctorhastie.svg
   :target: https://pypi.python.org/pypi/doctorhastie
   :alt: PyPI Package

.. image:: https://img.shields.io/travis/LuisAlejandro/doctorhastie.svg
   :target: https://travis-ci.org/LuisAlejandro/doctorhastie
   :alt: Travis CI

.. image:: https://coveralls.io/repos/github/LuisAlejandro/doctorhastie/badge.svg?branch=master
   :target: https://coveralls.io/github/LuisAlejandro/doctorhastie?branch=master
   :alt: Coveralls

.. image:: https://landscape.io/github/LuisAlejandro/doctorhastie/master/landscape.svg?style=flat
   :target: https://landscape.io/github/LuisAlejandro/doctorhastie/master
   :alt: Landscape

.. image:: https://readthedocs.org/projects/doctorhastie/badge/?version=latest
   :target: https://readthedocs.org/projects/doctorhastie/?badge=latest
   :alt: Read The Docs

.. image:: https://cla-assistant.io/readme/badge/LuisAlejandro/doctorhastie
   :target: https://cla-assistant.io/LuisAlejandro/doctorhastie
   :alt: Contributor License Agreement

.. image:: https://badges.gitter.im/LuisAlejandro/doctorhastie.svg
   :target: https://gitter.im/LuisAlejandro/doctorhastie
   :alt: Gitter Chat

.. _PyPIContents: https://github.com/LuisAlejandro/pypicontents

Doctor Hastie is an assistant to guess your pip dependencies from your code, without using a
requirements file.

Doctor Hastie will tell you which packages you need to install to satisfy the dependencies of
your project. It uses a simple AST visitor for detecting imports and `PyPIContents`_ to
search which packages contain these imports.

* Free software: GPL-3
* Documentation: https://doctorhastie.readthedocs.org

Table of Contents
-----------------

.. toctree::
   :maxdepth: 2

   installation
   usage
   api
   contributing
   authors
   history
   maintainer