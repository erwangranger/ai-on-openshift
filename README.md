# AI on OpenShift

Source code for the AI on OpenShift site, using [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

Rendered at [https://ai-on-openshift.io/](https://ai-on-openshift.io/)

## Goal

The AI on OpenShift site aims at being a one-stop shop for installation recipes, patterns, demos for various AI/ML tools and applications used in Data Science and Data Engineering projects running on OpenShift.

## Development

### Local development with MkDocs

* Prerequisites: Python >=3.7
* Install the `mkdocs-material` package from PyPI, either in your main Python environment or in a virtual environment: `pip install mkdocs-material`.
* A Pipfile is also provided. To make use of it, you can execute:

    ```bash
    pip install pipenv
    pipenv install
    pipenv shell
    ```

* From the root of the repo, launch `mkdocs serve`
* The documentation will be accessible at [http://127.0.0.1:8000](http://127.0.0.1:8000)
* All saved modifications are watched and rendered real time

### Contributions

* Create a branch (maintainers team) or fork the repo (other contributors)
* Develop locally as described above
* Submit a Pull Request to the `main` branch of the repo
