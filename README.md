# Proyecto nuevo con sphinx

https://www.sphinx-doc.org/en/master/tutorial/getting-started.html


## Instalar y crear proyecto

    python -m venv .venv
    ./venv/Scripts/activate
    (.venv)> python -m pip install sphinx
    (.venv)> sphinx-build --version
    (.venv)> sphinx-quickstart docs
    (.venv)> code .


## Instalar el tema Read the Docs

https://github.com/readthedocs/sphinx_rtd_theme

    (.venv)> pip install sphinx-rtd-theme

En **conf.py**:

    html_theme = 'sphinx_rtd_theme'
    html_show_sourcelink = False
    html_permalinks = False



