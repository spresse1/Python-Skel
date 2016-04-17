# MYMODULE

## CI Status

[![Build Status](https://travis-ci.org/spresse1/MYMODULE.svg?branch=master)](https://travis-ci.org/spresse1/MYMODULE)
[![codecov.io](https://codecov.io/github/spresse1/MYMODULE/coverage.svg?branch=master)](https://codecov.io/github/spresse1/MYMODULE?branch=master)
[![Codacy Badge](https://api.codacy.com/project/badge/grade/bdc343b447df40d895be50b251fee31e)](https://www.codacy.com/app/steve_7/MYMODULE)

## Purpose

## Use

## Documentation
To build the documentation, run:
`tox -e docs`

Currently this only builds html docs.  Other targets can be relatively easily added by modifying tox.ini.

## Testing
To test, run either:

1. `tox` (preferred)
2. `python setup.py test`

This module should have a 100% test coverage and tests are set to fail if this is not the case.

### Modifying tests

All tests are currently located in tests/ and (though untested) any tests using python's unittest module placed in this directory should run.


