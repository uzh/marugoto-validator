# maruval

Validator for [marugoto](https://github.com/uzh/marugoto) content

> Version 0.0.1

[![Build Status](https://travis-ci.org/uzh/maruval.svg?branch=master)](https://travis-ci.org/uzh/maruval)
[![codecov.io](https://codecov.io/gh/uzh/maruval/branch/master/graph/badge.svg)](https://codecov.io/gh/uzh/maruval)
[![PyPI version](https://badge.fury.io/py/maruval.svg)](https://badge.fury.io/py/maruval)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/python/black)

## Installing dependencies

*maruval* is a Python tool, so your machine needs Python and the Python package manager *pip* for installation. You should already have Python.

To check if you have *pip*, type `which pip3` and/or `which pip` into your command line. If either command returns a path to `pip`, you can proceed to `Installing maruval`.

To install *pip*, run the following command:

```bash
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py && python3 get-pip.py && rm get-pip.py
```

Now `which pip` should show a path to a *pip* executable

## Installing *maruval*

Once you have *Python* and *pip3*/*pip*, run the following:

```bash
pip3 install maruval
# or, from the git repo:
git clone https://github.com/uzh/maruval && cd maruval && python.setup.py install
```

## How to use maruval (showing optional flags):

```bash
maruval -f -nw <path_to_content>
```

* `-f`/`--fail-first` will stop *maruval* after first error
* `-nw`/`--no-warnings` will suppress warning messages

## Show help

```bash
maruval --help
```
