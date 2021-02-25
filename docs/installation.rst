.. highlight:: shell

============
Installation
============


Stable release
--------------

To install pypkgs_RW, run this command in your terminal:

.. code-block:: console

    $ pip install -u pypkgs_rw

This is the preferred method to install pypkgs_RW, as it will always install the most recent stable release.

If you don't have `pip`_ installed, this `Python installation guide`_ can guide
you through the process.

.. _pip: https://pip.pypa.io
.. _Python installation guide: http://docs.python-guide.org/en/latest/starting/installation/


From sources
------------

The sources for pypkgs_RW can be downloaded from the `Github repo`_.

You can either clone the public repository:

.. code-block:: console

    $ git clone git://github.com/wang-rui/pypkgs_rw

Or download the `tarball`_:

.. code-block:: console

    $ curl  -OL https://github.com/wang-rui/pypkgs_rw/tarball/main

Once you have a copy of the source, you can install it. The method of installation will depend on the packaging library being used.

For example, if `setuptools` is being used (a setup.py file is present), install pypkgs_rw with:

.. code-block:: console

    $ python setup.py install

If `poetry` is being used (poetry.lock and pyproject.toml files are present), install pypkgs_rw with:

.. code-block:: console

    $ poetry install


.. _Github repo: https://github.com/wang-rui/pypkgs_rw
.. _tarball: https://github.com/wang-rui/pypkgs_rw/tarball/master
