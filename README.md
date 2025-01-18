## Daddy's Boring Math Library

WORK IN PROGRESS - breaking up grscheller/boring-math mono-repo

Python project of packages of a mathematical nature.

### Overview:

The Boring Math library consists of Python PyPI namespace packages all
under an empty **bm.** "namespace."

* bm.integer-math
* bm.probability-distributions
* bm.pythagorean-triples
* bm.recursive-functions

The purpose of this collection of PyPI namespace projects is to host
and provide infrastructure for my Python mathematical hobby projects.

The project name was suggested by my then 13 year old daughter Mary.

### Documentation

[Detailed documentation](https://grscheller.github.io/boring-math-docs/)
for the Boring Math project.

### Source Code

GitHub source code subpackage repos:

* [bm.integer_math](https://github.com/grscheller/bm-integer-math)
* [bm.probability_distributions](https://github.com/grscheller/bm-probability-distributions)
* [bm.pythagorean_triples](https://github.com/grscheller/bm-pythagorean-triples)
* [bm.recursive_functions](https://github.com/grscheller/bm-recursive-functions)

### Documentation Generation

Using the bm.integer-math as an example, here is how one generates the
docs with [pdoc](https://pypi.org/project/pdoc/). The integer-math
project depends on both the grscheller.fp and grscheller.circular-array
projects.

```bash
   $ cd docs/integer_math/API/development/
   $ rm -r bm/ index.html search.js
   $ PYTHONPATH=~/devel/pypi/circular-array/src:~/devel/pypi/fp/src:~/devel/pypi/boring-math/src
   $ pdoc -o . bm.integer_math
```

