[![Codespaces Prebuilds](https://github.com/nogibjj/python-data-science-template/actions/workflows/codespaces/create_codespaces_prebuilds/badge.svg)](https://github.com/nogibjj/python-data-science-template/actions/workflows/codespaces/create_codespaces_prebuilds)

[![CI](https://github.com/nogibjj/python-data-science-template/actions/workflows/main.yml/badge.svg)](https://github.com/nogibjj/python-data-science-template/actions/workflows/main.yml)

# Template for Python Data Science projects
This is a Python template for Data Science projects with CI setup using GitHub Actions. It also provides a .devcontainer setup. It has all the standard libraries for a Data Science project.

# Directory Structure
```
.
├── Dockerfile
├── LICENSE
├── Makefile
├── README.md
├── requirements.txt
├── src
│   ├── lib
│   │   ├── __init__.py
│   │   └── func_utils.py
│   └── main.py
└── tests
    ├── __init__.py
    ├── test_lib.py
    └── test_main.py
```