========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - tests
      - | |travis| |appveyor| |requires|
        | |coveralls| |codecov|
        | |landscape| |scrutinizer| |codacy| |codeclimate|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |travis| image:: https://api.travis-ci.org/VolpeVorpale/python-tictactoe.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/VolpeVorpale/python-tictactoe

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/VolpeVorpale/python-tictactoe?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/VolpeVorpale/python-tictactoe

.. |requires| image:: https://requires.io/github/VolpeVorpale/python-tictactoe/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/VolpeVorpale/python-tictactoe/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/VolpeVorpale/python-tictactoe/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/VolpeVorpale/python-tictactoe

.. |codecov| image:: https://codecov.io/github/VolpeVorpale/python-tictactoe/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/VolpeVorpale/python-tictactoe

.. |landscape| image:: https://landscape.io/github/VolpeVorpale/python-tictactoe/master/landscape.svg?style=flat
    :target: https://landscape.io/github/VolpeVorpale/python-tictactoe/master
    :alt: Code Quality Status

.. |codacy| image:: https://img.shields.io/codacy/grade/inf.svg
    :target: https://www.codacy.com/app/VolpeVorpale/python-tictactoe
    :alt: Codacy Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/VolpeVorpale/python-tictactoe/badges/gpa.svg
   :target: https://codeclimate.com/github/VolpeVorpale/python-tictactoe
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/tictactoe.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/tictactoe

.. |wheel| image:: https://img.shields.io/pypi/wheel/tictactoe.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/tictactoe

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/tictactoe.svg
    :alt: Supported versions
    :target: https://pypi.org/project/tictactoe

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/tictactoe.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/tictactoe

.. |commits-since| image:: https://img.shields.io/github/commits-since/VolpeVorpale/python-tictactoe/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/VolpeVorpale/python-tictactoe/compare/v0.0.0...master


.. |scrutinizer| image:: https://img.shields.io/scrutinizer/quality/g/VolpeVorpale/python-tictactoe/master.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/VolpeVorpale/python-tictactoe/


.. end-badges

A library for playing tictactoe.

* Free software: MIT license

Installation
============

::

    pip install tictactoe

You can also install the in-development version with::

    pip install https://github.com/VolpeVorpale/python-tictactoe/archive/master.zip


Documentation
=============


To use the project:

.. code-block:: python

    import tictactoe
    tictactoe.longest()


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
