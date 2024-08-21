# DHTK website source code

This repository contains the source code for the DHTK website.The website is hosted on GitHub Pages: [https://dhtk-unil.github.io/dhtk.github.pages](https://dhtk-unil.github.io/dhtk.github.pages).


The MkDocs documentation is available in [./docs](./docs).

## Local development

To build the website locally, you need Python and to install the following:
```bash
pip install mkdocs
pip install mkdocs-material
pip install "mkdocstrings[python]"
```

Then, you can run the following command to build the website and serve it locally:
```bash
mkdocs serve
```

## Updating/improving documentation in progress

The documentation is currently being updated and improved. The following pages have been updated: 
Index (home), Installation, Getting Started and About.

TODO:
- User Guide
  - [ ] Document Auchinleck data source
  - [ ] Adapt documentation such that it corresponds well with the source code.
  - [ ] Fix any other mistake/inconsistency.
- Developer guide
  - [ ] Update procedure to create a new module.
  - [ ] Adapt documentation such that it corresponds well with the source code.
  - [ ] Fix any other mistake/inconsistency.
- FAQ
  - [ ] Update answers about DHTK Architecture and Community.
- API
  - [ ] Complete code documentation such that the API section is up to date.

## References

MkDocs: [https://www.mkdocs.org](https://www.mkdocs.org/user-guide/writing-your-docs/)

MkDocs Material: [https://squidfunk.github.io/mkdocs-material/reference](https://squidfunk.github.io/mkdocs-material/reference)