# Proximity and Boolean Query Search

This is a Python project for running boolean and proximity queries on a given set of research papers.

## File structure

The included files are:
1. processing.ipynb
2. RunQueries.ipynb
3. docs.pkl
4. inverted_index.pkl
5. positional_index.pkl

Run processing.ipynb first if you want to preprocess from scratch. RunQueries is for running queries in GUI.

## Installation
You need to clone to the directory. Make to sure to clone the ".pkl" files as they contain the indices.
You need a recent version of Python which should include:
- tkinter
- pickle
- re
- nltk

All packages except nltk come by default in the latest python versions.
I've added a cell in the python notebook to install nltk.

```bash
pip install nltk
```

## Running queries

In order to perform search.
1. Run the "RunQueries.ipynb" in a jupyter notebook environment
2. Run all cells from top to bottom for it to work.
3. Add proximity or boolean queries in their respective input boxes.
