Tutorial: Natural Language Processing in Python
=====

    This repo contains material for a workshop on Natural Language Processing with Python.

Environment Set up
-----

The code has been tested with Python `3.4` and `3.5`. This paragraph describes how to set up your environment locally.

Step 1: clone this repo::

    git clone https://github.com/bonzanini/nlp-tutorial
    cd nlp-tutorial

Step 2: create and activate a Python virtual environment::

    virtualenv --python=python3 nlp-venv
    source nlp-venv/bin/activate

Step 2 (alternative): create a Conda environment::

    conda create --name nlp-venv python=3.5
    source activate nlp-venv

Step 3: install libraries::

    pip install -r requirements.txt

This will download and install NLTK, scikit-learn and jupyter (plus dependencies).

Step 4: run Jupyter::

    jupyter notebook



Authors
-----

Main authors:

- Marco Bonzanini (`@MarcoBonzanini <http://www.twitter.com/marcobonzanini>`_)
- Miguel Martinez-Alvarez (`@MiguelMAlvarez <http://www.twitter.com/miguelmalvarez>`_)

Slides
-----

...

License
-----

Code (mainly in `notebooks` folder) under MIT license.

Documentation and slides under CC-BY license.

Data
-----

- Documents in `data/recipes` are public domain from Project Gutenberg
- Documents in `data/pyconuk2016` are the abstracts from https://github.com/PyconUK/2016.pyconuk.org

