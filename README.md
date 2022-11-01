# Welcome to My Python Project

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/dokempf/test-gha-python-package/CI)](https://github.com/dokempf/test-gha-python-package/actions?query=workflow%3ACI)
[![Documentation Status](https://readthedocs.org/projects/test-gha-python-package/badge/)](https://test-gha-python-package.readthedocs.io/)
[![codecov](https://codecov.io/gh/dokempf/test-gha-python-package/branch/main/graph/badge.svg)](https://codecov.io/gh/dokempf/test-gha-python-package)

## Installation

The Python packaage `testghapythonpackage` can be installed from PyPI:

```
python -m pip install testghapythonpackage
```

## Development installation

If you want to contribute to the development of `testghapythonpackage`, we recommend
the following editable installation from this repository:

```
git clone git@github.com:dokempf/test-gha-python-package.git
cd test-gha-python-package
python -m pip install --editable .[tests]
```

Having done so, the test suite can be run using `pytest`:

```
python -m pytest
```

## Acknowledgments

This repository was set up using the [SSC Cookiecutter for Python Packages](https://github.com/ssciwr/cookiecutter-python-package).
