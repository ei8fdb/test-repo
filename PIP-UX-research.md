## Introduction

This collection of resources explains the Python packaging ecosystem, and provides links to more detailed information.

## Key Python installation and packaging projects
All key python installation and packaging projects are listed with full explanation, links to repositories, IRC channels, and mailing lists on the [Python packaging wiki](https://packaging.python.org/key_projects/
).

### bandersnatch
A PyPI mirroring client designed to efficiently create a complete mirror of the contents of PyPI.

The [Python packaging user guide](https://packaging.python.org/key_projects/#bandersnatch) has a full explanation with mailing lists, repos and IRC channels.

### distlib
A library which implements low-level functions that relate to packaging and distribution of Python software.

The [Python packaging user guide](https://packaging.python.org/key_projects/#distlib) has a full explanation with mailing lists, repos and IRC channels.

### packaging
Core utilities for Python packaging used by pip and setuptools.

Most Python users rely on this library without needing to explicitly call it; developers of the other Python use its functionality to parse, discover, and otherwise handle dependency attributes.

The [Python packaging user guide](https://packaging.python.org/key_projects/#packaging) has a full explanation with mailing lists, repos and IRC channels.

### pip
The most popular tool for installing Python packages, included with modern versions of Python. It provides the essential core features for finding, downloading, and installing packages from PyPI and other Python package indexes.

The [Python packaging user guide](https://packaging.python.org/key_projects/#pip) has a full explanation with mailing lists, repos and IRC channels.

### Pipenv
Aims to bring the best of all packaging worlds to the Python world. It harnesses Pipfile, pip, and virtualenv into one single toolchain.

It aims to help users manage environments, dependencies, and imported packages on the command line.

The [Python packaging user guide](https://packaging.python.org/key_projects/#pip) has a full explanation with mailing lists, repos and IRC channels.

### pipfile

Pipfile and it's sister Pipfile.lock are a higher-level application-centric alternative to pip’s lower-level requirements.txt file.

[Python packaging user guide](https://packaging.python.org/key_projects/#pipfile)

### Python Packaging User Guide
The [Python packaging user guide](https://packaging.python.org/key_projects/#python-packaging-user-guide)

### readme_renderer
A library that package developers use to render their user documentation (README) files into HTML from markup languages

Developers call it on its own or via twine, as part of their release management process, to check that their package descriptions will properly display on PyPI.

The [Python packaging user guide](https://packaging.python.org/key_projects/#readme-renderer) has a full explanation with mailing lists, repos and IRC channels.

### setuptools
A collection of enhancements to the Python distutils that allow you to more easily build and distribute Python distributions, especially ones that have dependencies on other packages.

The [Python packaging user guide](https://packaging.python.org/key_projects/#easy-install) has a full explanation with mailing lists, repos and IRC channels.

### twine
The primary tool developers use to upload packages to the Python Package Index or other Python package indexes. It is a command-line program that passes program files and metadata to a web API.

The [Python packaging user guide](https://packaging.python.org/key_projects/#twine) has a full explanation with mailing lists, repos and IRC channels.

### virtualenv
A tool which uses the command-line path environment variable to create isolated Python Virtual Environments, much as venv does.

The [Python packaging user guide](https://packaging.python.org/key_projects/#virtualenv) has a full explanation with mailing lists, repos and IRC channels.

### Warehouse
The current codebase powering the Python Package Index (PyPI). It is hosted at pypi.org. The default source for pip downloads.

The [Python packaging user guide](https://packaging.python.org/key_projects/#warehouse) has a full explanation with mailing lists, repos and IRC channels.

### wheel
Offers the bdist_wheel setuptools extension for creating wheel distributions, also offers it's own command line utility for creating and installing wheels.

The [Python packaging user guide](https://packaging.python.org/key_projects/#wheel) has a full explanation with mailing lists, repos and IRC channels.
