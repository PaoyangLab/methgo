Installation
============

1. Obtain Python 3.8 and the standard ``venv`` module.

  .. note::
    MethGo depends on `SAMtools <http://www.htslib.org/>`_ and
    `BEDtools <http://bedtools.readthedocs.org/>`_, so please make sure you
    already have them on your server.

2. Create a virtual environment somewhere on your disk, and then activate it.

  ::

  $ python3.8 -m venv methgo_env
  $ source methgo_env/bin/activate


3. Download the source code and install the requirements.

  ::

  $ git clone https://github.com/paoyangchen-laboratory/methgo.git
  $ python -m pip install --upgrade pip setuptools wheel
  $ python -m pip install -r methgo/requirements/base.txt
  $ python -m pip install -r methgo/requirements/addition.txt

  pip will install the following packages:

  * `NumPy <http://www.numpy.org/>`_
  * `SciPy <http://www.scipy.org/>`_
  * `matplotlib <http://matplotlib.org/>`_
  * `pandas <https://pandas.pydata.org/>`_
  * `PySAM <https://pysam.readthedocs.io/>`_
  * `Biopython <http://biopython.org/>`_
  * `Cython <http://cython.org/>`_
  * `pybedtools <https://pythonhosted.org/pybedtools/>`_

4. Add your MethGo path to the PATH environment variable.
