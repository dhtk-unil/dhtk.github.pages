
Installation
============

Install Python
--------------

As DHTK is a Python module, make sure you have Python installed on your
system. You can do this in three different ways:

1. Manually search the common locations where your system saves
    applications.
2. You can use the search file options from you system to find the
    Python application.
3. You can type `python --version` on your command line or PowerShell
    (Windows).

If you don't have Python 3 installed, please [download
it](https://www.python.org/downloads/) and follow the instructions. We
recommend using the most up-to-date Python 3 version, but DHTK is
compatible with at least Python 3.7+.

Install Docker
--------------

In addition to Python 3, you are likely to use a local SPARQL endpoint
when using DHTK to search pre-processed data. This requires setting up a
Fuseki server container on the Docker application. To do so, you will
need to [download Docker](https://docs.docker.com/get-docker/) before
running DHTK.

!!! info "Note"

    DHTK may attempt to install Docker (macOS systems only) and set up all
    required containers and volumes.


Install DHTK
------------

DHTK can be installed as a regular Python module, using the package
installer for Python ([Python Package Index (PyPI)](https://pypi.org/project/pip/)):

```bash
pip install git+https://github.com/dhtk-unil/dhtk.git
```

[//]: # (    $ pip install git+https://github.com/dhtk-unil/dhtk.git)

Alternatively, you may download the [DHTK source
code](https://github.com/dhtk-unil/dhtk.git) in your preferred
format. Once you extract the DHTK files from the archive, you can access
them via command line (or PowerShell).

```bash
cd dhtk
python setup.py  # or
pip install .
```
    

Install extensions
-------------------
DHTK Extensions can be installed as a regular Python module, using the package
installer for Python ([Python Package Index (PyPI)](https://pypi.org/project/pip/)):


```bash
pip install git+https://github.com/dhtk-unil/<name_extension>.git
```

where `<name_extension>` has to be replaced with the name of the extension you wish to install. 
For now, the possible extensions are:

```bash
# Data sources
pip install git+https://github.com/dhtk-unil/dhtk_data_source_auchinleck.git
pip install git+https://github.com/dhtk-unil/dhtk_data_source_gutenberg.git

# Data storages
pip install git+https://github.com/dhtk-unil/dhtk_storage_docker.git

# Examples for creating new data sources
pip install git+https://github.com/dhtk-unil/dhtk_data_source_dummytriplestore.git
pip install git+https://github.com/dhtk-unil/dhtk_data_source_dummytei.git
pip install git+https://github.com/dhtk-unil/dhtk_data_source_dummynosql.git
pip install git+https://github.com/dhtk-unil/dhtk_data_source_dummysql.git
pip install git+https://github.com/dhtk-unil/dhtk_data_source_dummyembedded.git
```

Alternatively, you may download the DHTK source
code(for example for [Gutenberg](https://github.com/dhtk-unil/dhtk_data_source_gutenberg/archive/refs/heads/main.zip) or from the [Github repository](https://github.com/dhtk-unil/dhtk_data_source_gutenberg)) in your preferred
format. Once you extract the DHTK files from the archive, you can access
them via command line (or PowerShell).

```bash
cd dhtk_data_source_gutenberg
python setup.py  # or
pip install .
```

!!! info "Note"

    DHTK runs a number of system check to try to guarantee if can run
    without any problem. If this is the first time you're running it, keep
    in mind that it may take considerable time to complete the the full
    set.
