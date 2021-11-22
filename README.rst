PyLBFGS
=======

.. image:: https://travis-ci.org/qingquansong/pylbfgs.svg?branch=master
    :target: https://travis-ci.org/dqingquansong/pylbfgs


[This is a mirrored package for PyLBFGS pacakge authored by Lars Buitinck, Forest Gregg at (https://github.com/dedupeio/pylbfgs.git) in order to make flexible local changes.]

The original package is a Python wrapper around Naoaki Okazaki (chokkan)'s liblbfgs_ library
of quasi-Newton optimization routines (limited memory BFGS and OWL-QN).

This package aims to provide a cleaner interface to the LBFGS
algorithm than is currently available in SciPy_, and to provide the
OWL-QN algorithm to Python users.

Part of the Dedupe.io_ cloud service and open source toolset for de-duplicating and finding fuzzy matches in your data.


Installing
==========
Type::

    pip install pylbfgs-mirror


Hacking
=======
Type::

    pip install "pip>=10"
    pip install -r requirements.txt
    pip install -e .

To run the test suite::

    pytest tests


Authors
=======
PyLBFGS was written by Lars Buitinck.

Alexis Mignon submitted a patch for error handling.

.. _Dedupe.io: https://dedupe.io/

.. _Cython: http://cython.org/

.. _liblbfgs: http://chokkan.org/software/liblbfgs/

.. _pytest: http://doc.pytest.org/en/latest/

.. _NumPy: http://numpy.scipy.org/

.. _SciPy: http://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.fmin_l_bfgs_b.html

.. _setuptools: http://pypi.python.org/pypi/setuptools
