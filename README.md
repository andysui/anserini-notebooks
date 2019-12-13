# Anserini Notebooks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/castorini/anserini-notebooks/master)
[![Generic badge](https://img.shields.io/badge/Lucene-v8.3.0-brightgreen.svg)](https://archive.apache.org/dist/lucene/java/8.3.0/)
[![Maven Central](https://img.shields.io/maven-central/v/io.anserini/anserini?color=brightgreen)](https://search.maven.org/search?q=a:anserini)
[![PyPI](https://img.shields.io/pypi/v/pyserini?color=brightgreen)](https://pypi.org/project/pyserini/)

This repo holds static copies of notebooks for the [Anserini](https://github.com/castorini/anserini) IR toolkit (Java) and [Pyserini](https://github.com/castorini/pyserini) (Python interface to Anserini).
There are two ways to play with the notebooks here, using Colab and Binder.

## Colab

The notebooks in this repo are sync'ed (by hand) with notebooks in Colab.
These online demos provide a low-effort way to try out Anserini and Pyserini features:

+ `anserini_robust04_demo.ipynb`: [Anserini demo on Robust04](https://colab.research.google.com/drive/1s44ylhEkXDzqNgkJSyXDYetGIxO9TWZn)
+ `pyserini_robust04_demo.ipynb`: [Pyserini demo on Robust04](https://colab.research.google.com/drive/1wiDOnjsPMZzrleQF-GnE5W6VsF7biuXH)
+ `pyserini_msmarco_passage_demo.ipynb`: [Pyserini demo on MS MARCO passage retrieval task](https://colab.research.google.com/drive/1nY1bjwop3Enygrks-208EilhiCYmYKT6)

Click "Open in Playground" and you'll be able to replicate our results!

## Binder

This entire repo is configured with work with [Binder](https://mybinder.org/).
Click the "launch binder" icon on the top-left corner to initialize an executable environment around these notebooks.

## Pre-Built Indexes

For convenience, we've pre-built a few common indexes, available to download [here](https://git.uwaterloo.ca/jimmylin/anserini-indexes).

