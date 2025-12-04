Installation
============

PyHazards requires Python 3.8+ and can be installed using pip. We recommend using a conda environment for installation.

Installing PyHazards
--------------------

Base install:

.. code-block:: bash

    pip install pyhazards

PyTorch notes (Python 3.8, CUDA 12.6 example):

- Install the matching PyTorch wheel first, then install PyHazards.
- Example (CUDA 12.6):

  .. code-block:: bash

      pip install torch --index-url https://download.pytorch.org/whl/cu126
      pip install pyhazards



Requirements
------------

- Python >= 3.8
- PyTorch == 2.3.0
