# Boring Math Library

Python project of packages of a mathematical nature. The purpose
of this collection is to host and provide infrastructure for my
Python mathematical hobby projects.

- integer-math - number theory and combinatorics
- probability-distributions - visually data & probability distributions
- pythagorean-triples - generating Pythagorean Triples
- recursive-functions - recursive function implementations

The library's name was suggested by my then 13 year old daughter Mary.

## Boring Math Library (`bm`)

| Python Package | Projects (PyPI) | Source Code (GitHub) |
|:-------------- |:--------------- |:-------------------- |
| bm.integer_math | [bm.integer-math][11] | [dtools-circular-array][21] |
| bm.probability_distributions | [bm.probability-distributions][12] | [bm-probability-distributions][22] |
| bm.pythagorean_triples | [bm.pythagorean-triples][13] | [bm-pythagorean-triples][23] |
| bm.recursive_functions | [bm.recursive-functions][14] | [bm-recursive-functions][24] |

#### Documentation Generation

Using the bm.integer-math as an example, here is how one generates
the docs with [pdoc](https://pypi.org/project/pdoc/). The integer-math
project depends on both dtools.fp and dtools.circular-array projects.
Refer to the pyproject.toml for compatible versions to install in the
virtual environment.

```bash
    cd docs/integer_math/API/development/
    rm -r bm/ index.html search.js
    PYTHONPATH=~/devel/pypi/boring-math/src
    pdoc -o . bm.integer_math
```

[11]: https://pypi.org/project/bm.integer-math/
[12]: https://pypi.org/project/bm.probability-distributions/
[13]: https://pypi.org/project/bm.pythagorean-triples/
[14]: https://pypi.org/project/bm.recursive-functions/
[21]: https://github.com/grscheller/bm-integer-math/
[22]: https://github.com/grscheller/bm-probability-distributions/
[23]: https://github.com/grscheller/bm-pythagorean-triples/
[24]: https://github.com/grscheller/bm-recursive-functions/
