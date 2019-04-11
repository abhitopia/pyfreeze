========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/pyfreeze/badge/?style=flat
    :target: https://readthedocs.org/projects/pyfreeze
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/abhitopia/pyfreeze.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/abhitopia/pyfreeze

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/abhitopia/pyfreeze?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/abhitopia/pyfreeze

.. |requires| image:: https://requires.io/github/abhitopia/pyfreeze/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/abhitopia/pyfreeze/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/abhitopia/pyfreeze/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/abhitopia/pyfreeze

.. |version| image:: https://img.shields.io/pypi/v/pyfreeze.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/pyfreeze

.. |commits-since| image:: https://img.shields.io/github/commits-since/abhitopia/pyfreeze/v0.0.1.svg
    :alt: Commits since latest release
    :target: https://github.com/abhitopia/pyfreeze/compare/v0.0.1...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/pyfreeze.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/pyfreeze

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/pyfreeze.svg
    :alt: Supported versions
    :target: https://pypi.org/project/pyfreeze

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/pyfreeze.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/pyfreeze


.. end-badges

A small library to easily allow freezing, unfreezing and differential learning rates on weights of Pytorch models.

* Free software: MIT license

Installation
============

::

    pip install pyfreeze

Documentation
=============


https://pyfreeze.readthedocs.io/


Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
