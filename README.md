Template for the Read the Docs tutorial
=======================================
[![Read the Docs](https://img.shields.io/readthedocs/tryreadthedocs-by-daemo00?style=plastic)](https://tryreadthedocs-by-daemo00.readthedocs.io)

This GitHub template includes fictional Python library
with some basic Sphinx docs.

Read the tutorial here:

https://docs.readthedocs.io/en/stable/tutorial/

Generate the docs locally
----

```shell
pip install -e ".[docs]"
cd docs
make html
```

Docs are autogenerated by https://readthedocs.org.