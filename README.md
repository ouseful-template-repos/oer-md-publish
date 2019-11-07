# oer-md-publish
Template repo for autobuilding nbsphinx sites

This template repository can be used as a basis for creating documentation sites that are auto-built using CircleCI.

CircleCI uses Spninx / nbSphinx to produce the a website in `gh-pages` from text and Jupyter notebook documents.

Jupytext is installed so that text files (`.py`, `.md`, etc) can be executed as notebooks via Jupytext.

Code execution is disabled by default in the `nbsphinx` configuration file (`conf.py`).


## Example README
A reimagining of the OpenLearn Unit [XXX](https://www.open.edu/openlearn).

*Check there for rights information until I sort out boilerplate here...*

To view the automatically published pages built from the pages in this repository, go to: https://GITORG.github.io/GITREPO
