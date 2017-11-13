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

   read_table
   read_csv
   read_fwf
   read_msgpack


Constructor
~~~~~~~~~~~

.. currentmodule:: pandas

.. autosummary::
   :toctree: generated/

   Series

Attributes
~~~~~~~~~~
**Axes**
  * **index**: axis labels

.. autosummary::
   :toctree: generated/

   Series.values
   Series.dtype
   Series.ftype
   Series.shape
   Series.nbytes
   Series.ndim
   Series.size
   Series.strides
   Series.itemsize
   Series.base
   Series.T
   Series.memory_usage
   Series.asobject
   
   
..
    .. autosummary::
       :toctree: generated/
       :template: autosummary/accessor.rst

       Series.str
       Series.cat
       Series.dt
       Series.plot


