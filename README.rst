Tutorial: Natural Language Processing in Python
=====

This repo contains material for a workshop on Natural Language Processing with Python.

Audience
-----

The target audience of this workshop are students, researchers, developers, hobbyists and anyone interested in knowing more about Natural Language Processing and Text Analytics.

Some very basic knowledge of Python is assumed (e.g. if you have seen some Python script before, you're good to go), but no previous NLP knowledge is required.


Presentations
-----

Different versions of this workshop have been delivered at different events:

- PyCon UK 2016: 3h session (slides ``presentations/2016-pyconuk-slides.pdf``)
- PyCon Ireland 2016: 1.5h session (slides ``presentations/2016-pyconie-slides.pdf``)
- PyCon Italy 2017: 3.5h session (slides ``presentations/2017-pyconitaly-slides.pdf``)


Environment Set up
-----

The code has been tested with Python ``3.4`` and ``3.5``. Support for Python ``2.7`` is best-effort, if you find an issue please report it.

This paragraph describes how to set up your environment locally.

Step 1 - clone this repo::

    git clone https://github.com/bonzanini/nlp-tutorial
    cd nlp-tutorial

Step 2 - create and activate a Python virtual environment::

    virtualenv nlp-venv
    source nlp-venv/bin/activate

Step 2 (alternative) - create a Conda environment::

    conda create --name nlp-venv python=3.5
    source activate nlp-venv

Step 3 - install libraries::

    pip install -r requirements.txt

This will download and install NLTK, scikit-learn and jupyter (plus dependencies).

NLTK requires some data to be installed separately (more details on `the NLTK website <http://www.nltk.org/data.html>`_).

From the command line, you can download the required packages::

    python -m nltk.downloader punkt stopwords reuters

Alternatively, from a Python interactive shell::

    >>> import nltk
    >>> nltk.download()

Then use the GUI to select the requires packages (punkt, stopwords, reuters).

Tip: even if you can use "all" as package name to install all the NLTK data, it's not a great thing to do over a flakey conference wi-fi. This will download approx. 2Gb and if we all do it at the same time we'll kill the conference wi-fi :)

Finally - run Jupyter::

    jupyter notebook

In order to test that your environment is correctly set. Please open the notebook "00 Environment Test" and follow the instructions.


matplotlib backend issues
-----

There might be a few issues related to ``matplotlib`` backends as described `on their documentation <http://matplotlib.org/faq/virtualenv_faq.html>`_, especially on macOS.

By editing/creating the file ``~/.matplotlib/matplotlibrc`` with the following line::

    backend: TkAgg

the issue should be fixed. If not, please refer to the `matplotlib docs <http://matplotlib.org/faq/virtualenv_faq.html>`_


Authors
-----

Main authors:

- Marco Bonzanini (`@MarcoBonzanini <http://www.twitter.com/marcobonzanini>`_)
- Miguel Martinez-Alvarez (`@MiguelMAlvarez <http://www.twitter.com/miguelmalvarez>`_)


License
-----

Code (mainly in `notebooks` folder) under MIT license.

Documentation and slides under CC-BY license.


Data
-----

- Documents in `data/recipes` are public domain from Project Gutenberg
- Documents in `data/pyconuk2016` are the abstracts from https://github.com/PyconUK/2016.pyconuk.org

