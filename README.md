# Intro to Network Analysis with igraph

## Installation Instructions

Installation can be non-trivial. But, the following steps should work on any Windows computer:

* Create an anaconda environment that runs python3.5 (installing everything)
* Download the wheel here: https://www.lfd.uci.edu/~gohlke/pythonlibs/#python-igraph
* Change directory to where the above is saved and run: `python -m pip install *.whl`
* Run `Conda install pycairo`
* Modify file based on https://github.com/igraph/python-igraph/commit/8864b46849b031a3013764d03e167222963c0f5d
* But, in the above modification, change the last line to `return result.decode("utf-8"), {'isolated': True}`
