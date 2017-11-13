Small test repo for the the pandas API documentation.

Required dependencies:

- sphinx
- pandas (latest released version is fine)
- IPython (for its sphinx extensions)
- numpydoc (needs master version: ``pip install git+https://github.com/numpy/numpydoc.git``

(vendored version of numpydoc is included in the source)

To build the docs::

    python make.py html
   
To start fresh, first do a make clean::

    python make.py clean

