# Cookiecutter Hatch PyPackage


|         |                                    |
|---------|------------------------------------|
| Details | [![License - MIT][MIT-image]][MIT-link] [![GitHub Sponsors][sponsor-image]][sponsor-link] |
| Features | [![Hatch project][hatch-image]][hatch-link] [![Pip - uv][uv-image]][uv-link] [![linting - Ruff][ruff-image]][ruff-link] [![types - mypy][mypy-image]][mypy-link] [![test - pytest][pytest-image]][pytest-link] [![Github Actions][github-actions]][precommit-link]  [![linting - precommit][precommit-image]][precommit-link] [![docs - mkdocs][mkdocs-image]][mkdocs-link] |



## ✨ Features

* [X] Lightweight starter
* [X] [`Hatch`](https://hatch.pypa.io/latest/install/) package management
* [X] [`uv`](https://github.com/astral-sh/uv) package lock, install and resolving
* [X] Linting and formatting with [`ruff`](https://github.com/charliermarsh/ruff)
* [X] Type checking with [`mypy`](https://github.com/python/mypy)
* [X] Unit tests with [`pytest`](https://github.com/pytest-dev/pytest) with optional asyncio setup.
* [X] Automate and standardize testing with [Hatch-env-matrices]
* [X] Documentation with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) and docstring reference support with [mkdocstrings](https://mkdocstrings.github.io/).
* [X] Ready-to-use [GitHub Actions](https://help.github.com/en/actions/automating-your-workflow-with-github-actions) pipelines with `dependabot`, `release-drafter`, `labeler`, `publish to PYPI workflows`, `publish to test PYPI workflows` & more.
* [X] [hatch-pip-compile]: *experimental* support for lock-files,
* [X] [pyproject.toml]: all package, build and tool configuration in one file,
* [X] [coverage]: tool for measuring code coverage of Python programs with pytest integration,
* [X] [pre-commit]: pre-commit git hooks that make your life easier,
* [X] [Markdown]: instead of reStructuredText, Markdown is used consistently for all text files,
* [X] [src-layout]: the actual Python package is kept under a `src` folder avoiding many common errors.

## 💫 Quickstart

Generate the project:

```bash
cookiecutter https://github.com/KingMichaelPark/cookiecutter-pypackage
```

The generator will automatically call `hatch env create & git init` at the end.

Then, for the `GitHub Actions pipelines` to work correctly, you should:

* Enable the GitHub repository in `Codecov`.
* Set `CODECOV_TOKEN` in your GitHub repository secrets. You can find in the Codecov settings of the corresponding project.
* Enable `GitHub Pages` using the `GitHub Actions` source.
* Option to publish to Test [`PyPI`](https://test.pypi.org/) for testing.
* Configure the [Trusted Publisher method on PyPI](https://docs.pypi.org/trusted-publishers/creating-a-project-through-oidc/): it's a modern and secure method to push your package to PyPI.


## License

This project is licensed under the terms of the
[MIT](https://github.com/KingMichaelPark/cookiecutter-pypackage/blob/main/LICENSE)
license.


[cookiecutter]: https://cookiecutter.readthedocs.io/
[github-actions]: https://img.shields.io/badge/GitHub%20Actions-2088FF.svg?style=flat&logo=GitHub-Actions&logoColor=white
[Hatch-env-matrices]: https://hatch.pypa.io/dev/config/environment/advanced/#matrix
[hatch-pip-compile]: https://github.com/juftin/hatch-pip-compile
[cookiecutter-pypackage]: https://github.com/audreyfeldroy/cookiecutter-pypackage
[pre-commit]: https://pre-commit.com/
[mkdocs]: https://www.mkdocs.org/
[Markdown]: https://www.markdownguide.org/
[src-layout]: https://packaging.python.org/en/latest/discussions/src-layout-vs-flat-layout/
[pytest]: https://docs.pytest.org/
[coverage]: https://coverage.readthedocs.io/
[mypy]: https://mypy-lang.org/
[ruff]: https://beta.ruff.rs/
[pyproject.toml]: https://hatch.pypa.io/latest/config/metadata/

[hatch-image]: https://img.shields.io/badge/%F0%9F%A5%9A-hatch-4051b5.svg
[hatch-link]: https://github.com/pypa/hatch
[ruff-image]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json
[ruff-link]: https://github.com/charliermarsh/ruff
[mypy-image]: https://img.shields.io/badge/Types-mypy-blue.svg
[mypy-link]: https://mypy-lang.org/
[pytest-image]: https://img.shields.io/badge/Pytest-0A9EDC.svg?style=flat&logo=Pytest&logoColor=white
[pytest-link]:  https://docs.pytest.org/
[mkdocs-image]: https://img.shields.io/badge/Docs-mkdocs-blue.svg
[mkdocs-link]: https://www.mkdocs.org/
[precommit-image]: https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white
[precommit-link]:  https://pre-commit.com/
[MIT-image]: https://img.shields.io/badge/License-MIT-9400d3.svg
[MIT-link]: LICENSE
[sponsor-image]: https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=ff69b4
[sponsor-link]: https://github.com/sponsors/KingMichaelPark
[uv-link]: https://github.com/astral-sh/uv
[uv-image]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/uv/main/assets/badge/v0.json
