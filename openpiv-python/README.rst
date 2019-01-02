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

.. |docs| image:: https://readthedocs.org/projects/openpiv-python/badge/?style=flat
    :target: https://readthedocs.org/projects/openpiv-python
    :alt: Documentation Status


.. |travis| image:: https://travis-ci.org/alexlib/openpiv-python.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/alexlib/openpiv-python

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/alexlib/openpiv-python?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/alexlib/openpiv-python

.. |requires| image:: https://requires.io/github/alexlib/openpiv-python/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/alexlib/openpiv-python/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/alexlib/openpiv-python/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/alexlib/openpiv-python

.. |version| image:: https://img.shields.io/pypi/v/openpiv.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/openpiv

.. |commits-since| image:: https://img.shields.io/github/commits-since/alexlib/openpiv-python/v0.21.2.svg
    :alt: Commits since latest release
    :target: https://github.com/alexlib/openpiv-python/compare/v0.21.2...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/openpiv.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/openpiv

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/openpiv.svg
    :alt: Supported versions
    :target: https://pypi.org/project/openpiv

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/openpiv.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/openpiv


.. end-badges

Open Source Particle Image Velocimetry

* Free software: MIT license

Installation
============

::

    pip install openpiv

Documentation
=============


https://openpiv-python.readthedocs.io/


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
