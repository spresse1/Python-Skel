# Python-Skel

## CI Status

[![Build Status](https://travis-ci.org/spresse1/Python-Skel.svg?branch=master)](https://travis-ci.org/spresse1/Python-Skel)
[![codecov.io](https://codecov.io/github/spresse1/Python-Skel/coverage.svg?branch=master)](https://codecov.io/github/spresse1/Python-Skel?branch=master)
[![Codacy Badge](https://api.codacy.com/project/badge/grade/bdc343b447df40d895be50b251fee31e)](https://www.codacy.com/app/steve_7/Python-Skel)

## Purpose

## Use

## Documentation
To build the documentation, run:
`tox -e docs`

To build a target other than html, set the environment variable DOC_TARGET.  Valid values are the same as those for sphinx.

## Testing
To test, run either:

1. `tox` (preferred)
2. `python setup.py test`

This module should have a 100% test coverage and tests are set to fail if this is not the case.

### Modifying tests

All tests are currently located in tests/ and (though untested) any tests using python's unittest module placed in this directory should run.


