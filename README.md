# Boring Math Library

Python project of packages of a mathematical nature.

## Overview

The Boring Math library consists of Python PyPI namespace packages all
under the **bm.** namespace.

- integer-math - number theory and combinatorics
- probability-distributions - visually data & probability distributions
- pythagorean-triples - generating Pythagorean Triples
- recursive-functions - recursive function implementations

The purpose of this collection of PyPI namespace projects is to host
and provide infrastructure for my Python mathematical hobby projects.

The library's name was suggested by my then 13 year old daughter Mary.

## PyPI

Boring math projects on PyPI:

- [bm.integer-math](https://pypi.org/project/bm.integer-math/)
- [bm.probability-distributions](https://pypi.org/project/bm.probability-distributions/)
- [bm.pythagorean-triples](https://pypi.org/project/bm.pythagorean-triples/)
- [bm.recursive-functions](https://pypi.org/project/bm.recursive-functions/)

## Source Code

GitHub source code repos:

- [bm-integer-math](https://github.com/grscheller/bm-integer-math/)
- [bm-probability-distributions](https://github.com/grscheller/bm-probability-distributions/)
- [bm-pythagorean-triples](https://github.com/grscheller/bm-pythagorean-triples/)
- [bm-recursive-functions](https://github.com/grscheller/bm-recursive-functions/)

## Documentation Generation

Using the bm.integer-math as an example, here is how one generates the
docs with [pdoc](https://pypi.org/project/pdoc/). The integer-math
project depends on both the grscheller.fp and grscheller.circular-array
projects.

```bash
    cd docs/integer_math/API/development/
    rm -r bm/ index.html search.js
    PYTHONPATH=~/devel/pypi/circular-array/src:~/devel/pypi/fp/src:~/devel/pypi/boring-math/src
    pdoc -o . bm.integer_math
```
