# How to customise this template

1. Name your repository with the name `fileformats-<SUBPACKAGE-TO-ADD-EXTRAS-TO>-extras`
1. Rename the `fileformats/extras/CHANGEME` directory to the name of the fileformats subpackage the extras are for
1. Search and replace "CHANGEME" with the name of the fileformats subpackage the extras are to be added
1. Replace name + email placeholders in `pyproject.toml` for developers and maintainers
1. Implement selected "extras" by implementing functions decorated by one of the `*_extra` hooks defined in the target fileformats class (see the [extras developer guide](https://arcanaframework.github.io/fileformats/developer/extras.html))
1. Ensure that the decorated functions are imported into the extras package root, i.e. `fileformats/extras/CHANGEME`
1. Delete these instructions in this README

...

# FileFormats-CHANGEME Extras

[![CI/CD](https://github.com/arcanaframework/fileformats-CHANGEME/actions/workflows/ci-cd.yml/badge.svg)](https://github.com/arcanaframework/fileformats-CHANGEME/actions/workflows/ci-cd.yml)
[![Codecov](https://codecov.io/gh/arcanaframework/fileformats-CHANGEME/branch/main/graph/badge.svg?token=UIS0OGPST7)](https://codecov.io/gh/arcanaframework/fileformats-CHANGEME)
[![Latest Version](https://img.shields.io/pypi/v/fileformats-CHANGEME-extras.svg)](https://pypi.python.org/pypi/fileformats-CHANGEME-extras/)
[![Documentation Status](https://img.shields.io/badge/docs-latest-brightgreen.svg?style=flat)](https://arcanaframework.github.io/fileformats/)

This is an extras module for the
[fileformats-CHANGEME](https://github.com/ArcanaFramework/fileformats-CHANGEME) package, which provides
additional functionality to format classes (i.e. aside from basic identification and validation), such as
conversion tools, metadata parsers, test data generators, etc...

## Quick Installation

This extension can be installed for Python 3 using *pip*::

    $ pip3 install fileformats-CHANGEME-extras

This will install the core package and any other dependencies

## License

This work is licensed under a
[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/)

[![Creative Commons Attribution 4.0 International License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
