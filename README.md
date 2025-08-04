# Boring Math Library - PROJECT MOVED

Effort moved to [boring-math](https://pypi.org/project/boring-math/) on PyPI.
When I chose `bm` namespace name I did not realize the base name was already
taken.

Collection of Python PyPI projects of a mathematical nature. All under
the `bm` namespace. The purpose of this collection is to host and
provide infrastructure for my Python mathematical hobby projects.

- integer-math - number theory and combinatorics
- probability-distributions - visually data & probability distributions
- pythagorean-triples - generating Pythagorean Triples
- recursive-functions - recursive function implementations

The library's name was suggested by my then 13 year old daughter Mary.

## Boring Math `bm` namespace projects

| Python Package | Projects (PyPI) | Source Code (GitHub) |
|:-------------- |:--------------- |:-------------------- |
| bm.integer_math | [bm.integer-math][11] | [grscheller/bm-integer-math][21] |
| bm.probability_distributions | [bm.probability-distributions][12] | [grscheller/bm-probability-distributions][22] |
| bm.pythagorean_triples | [bm.pythagorean-triples][13] | [grscheller/bm-pythagorean-triples][23] |
| bm.recursive_functions | [bm.recursive-functions][14] | [grscheller/bm-recursive-functions][24] |

### Documentation Generation

Using the bm.integer-math as an example, here is how one generates
the docs with [pdoc](https://pypi.org/project/pdoc/). The integer-math
project depends on both dtools.fp and dtools.circular-array projects.
Refer to the pyproject.toml for compatible versions to install in the
virtual environment.

```bash
    cd ~/devel/pypi/bm/boring-math-docs/integer-math/API/development
    rm -r bm/ index.html search.js
    PYTHONPATH=~/devel/pypi/bm/bm-integer-math:~/devel/pypi/dtools/dtools-circular-array:~/devel/pypi/dtools/dtools-fp
    pdoc -o . bm.integer_math
```

### More Information

This repo itself, as well as all the Boring Math namespace projects, are
licensed under the Apache License Version 2.0, January 2004.

See [CHANGELOG.md](./CHANGELOG.md) for ongoing changes.

This collections is not associated with either the
`https://pypi.org/project/bm` PyPI project or the
`https://github.com/cym13/bookmark` GitHub repo.


[11]: https://pypi.org/project/bm.integer-math/
[12]: https://pypi.org/project/bm.probability-distributions/
[13]: https://pypi.org/project/bm.pythagorean-triples/
[14]: https://pypi.org/project/bm.recursive-functions/
[21]: https://github.com/grscheller/bm-integer-math/
[22]: https://github.com/grscheller/bm-probability-distributions/
[23]: https://github.com/grscheller/bm-pythagorean-triples/
[24]: https://github.com/grscheller/bm-recursive-functions/
