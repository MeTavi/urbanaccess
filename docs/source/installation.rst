Installation
=====================

UrbanAccess relies on a number of libraries in the scientific Python stack which can be easily installed using the `Anaconda`_ python distribution which can be downloaded `here <https://www.continuum.io/downloads>`__.

Dependencies
------------

* requests >= 2.9.1
* pandas >= 0.17.0
* numpy >= 1.11
* osmnet >= 0.1a
* pandana >= 0.2.0
* matplotlib >= 2.0
* geopy >= 1.11.0
* pyyaml >= 3.11
* scikit-learn >= 0.17.1

Dependencies can be installed through the ``conda-forge`` and ``udst`` channels. To add these as default installation channels for conda, run this code in a terminal::

    conda config --add channels udst
    conda config --add channels conda-forge

Current status
--------------

UrbanAccess is currently in a alpha release and only compatible with Python 2.x. Further code refinements are expected.

*Forthcoming improvements:*

* Unit tests
* Python 3

Install the latest release
--------------------------

conda
~~~~~~
conda installation is forthcoming.

pip
~~~~~~
UrbanAccess is available on PyPI and can be installed with::

    pip install -U urbanaccess

Development Installation
------------------------

UrbanAccess is currently in a alpha release and further code refinements are expected. As such, it is suggested to install using the ``develop`` command rather than ``install``. Make sure you are using the latest version of the code base by using git's ``git pull`` inside the cloned repository.

To install UrbanAccess follow these steps:

1. Git clone the `UrbanAccess repo <https://github.com/udst/urbanaccess>`__
2. in the cloned directory run: ``python setup.py develop``

To update to the latest development version:

Use ``git pull`` inside the cloned repository


.. _Anaconda: http://docs.continuum.io/anaconda/