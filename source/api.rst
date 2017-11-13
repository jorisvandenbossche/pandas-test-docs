.. currentmodule:: pandas
.. _api:

*************
API Reference
*************

This page gives an overview of all public pandas objects, functions and
methods. In general, all classes and functions exposed in the top-level
``pandas.*`` namespace are regarded as public.

Further some of the subpackages are public, including ``pandas.errors``,
``pandas.plotting``, and ``pandas.testing``. Certain functions in the the
``pandas.io`` and ``pandas.tseries`` submodules are public as well (those
mentioned in the documentation). Further, the ``pandas.api.types`` subpackage
holds some public functions related to data types in pandas.


.. autosummary::
   :toctree: generated/

   read_csv


Constructor
~~~~~~~~~~~

.. currentmodule:: pandas

.. autosummary::
   :toctree: generated/

   Series

Methods
~~~~~~~

.. autosummary::
   :toctree: generated/

   Series.mean
   Series.std
   Series.max
   Series.min
   
   
..
    .. autosummary::
       :toctree: generated/
       :template: autosummary/accessor.rst

       Series.str
       Series.cat
       Series.dt
       Series.plot


