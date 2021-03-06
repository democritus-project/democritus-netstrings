# Democritus Netstrings

[![PyPI](https://img.shields.io/pypi/v/d8s-netstrings.svg)](https://pypi.python.org/pypi/d8s-netstrings)
[![CI](https://github.com/democritus-project/d8s-netstrings/workflows/CI/badge.svg)](https://github.com/democritus-project/d8s-netstrings/actions)
[![Lint](https://github.com/democritus-project/d8s-netstrings/workflows/Lint/badge.svg)](https://github.com/democritus-project/d8s-netstrings/actions)
[![codecov](https://codecov.io/gh/democritus-project/d8s-netstrings/branch/main/graph/badge.svg?token=V0WOIXRGMM)](https://codecov.io/gh/democritus-project/d8s-netstrings)
[![The Democritus Project uses semver version 2.0.0](https://img.shields.io/badge/-semver%20v2.0.0-22bfda)](https://semver.org/spec/v2.0.0.html)
[![The Democritus Project uses black to format code](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![License: LGPL v3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://choosealicense.com/licenses/lgpl-3.0/)

Democritus functions<sup>[1]</sup> for working with Netstrings.

[1] Democritus functions are <i>simple, effective, modular, well-tested, and well-documented</i> Python functions.

We use `d8s` (pronounced "dee-eights") as an abbreviation for `democritus` (you can read more about this [here](https://github.com/democritus-project/roadmap#what-is-d8s)).

## Installation

```
pip install d8s-netstrings
```

## Usage

You import the library like:

```python
from d8s_netstrings import *
```

Once imported, you can use any of the functions listed below.

## Functions

  - ```python
    def string_to_netstring_ascii(string: str, *args):
        """Convert the given string to a netstring (and return it's ascii representation)."""
    ```
  - ```python
    def string_to_netstring_hex(string: str, *args):
        """Convert the given string to a netstring (and return it's hex representation)."""
    ```
  - ```python
    def netstring_ascii_to_netstring_hex(netstring_ascii: str):
        """Convert a netstring (represented as ascii) to its hex representation."""
    ```
  - ```python
    def netstring_hex_to_netstring_ascii(netstring_hex: str):
        """Convert a netstring (represented as hex) to its ascii representation."""
    ```
  - ```python
    def netstring_ascii_to_string(netstring_ascii: str):
        """Get the string portion of the given netstring (represented as ascii)."""
    ```
  - ```python
    def netstring_hex_to_string(netstring_hex: str):
        """Get the string portion of the given netstring (represented as hex)."""
    ```

## Development

👋 &nbsp;If you want to get involved in this project, we have some short, helpful guides below:

- [contribute to this project 🥇][contributing]
- [test it 🧪][local-dev]
- [lint it 🧹][local-dev]
- [explore it 🔭][local-dev]

If you have any questions or there is anything we did not cover, please raise an issue and we'll be happy to help.

## Credits

This package was created with [Cookiecutter](https://github.com/audreyr/cookiecutter) and Floyd Hightower's [Python project template](https://github.com/fhightower-templates/python-project-template).

[contributing]: https://github.com/democritus-project/.github/blob/main/CONTRIBUTING.md#contributing-a-pr-
[local-dev]: https://github.com/democritus-project/.github/blob/main/CONTRIBUTING.md#local-development-
