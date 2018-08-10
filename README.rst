
======
The Bias and Fairness Audit Toolkit for Machine Learning
======


.. figure:: src/aequitas_webapp/static/images/aequitas_header.png
   :scale: 50 %


----------------------------------------------
Aequitas
----------------------------------------------

Aequitas is an open-source bias audit toolkit for machine learning developers, analysts, and policymakers to audit machine learning models for discrimination and bias, and to make informed and equitable decisions around developing and deploying predictive risk-assessment tools.

`Learn more about the project <http://dsapp.uchicago.edu/aequitas/>`_.

Demo
====

`See what Aequitas can do <http://aequitas.dssg.io/>`_.

Sample Jupyter Notebook
====

 `Explore bias analysis of the COMPAS data <https://github.com/dssg/aequitas/blob/master/docs/source/examples/compas_demo.ipynb>`_ using the Aequitas library.

Documentation
====

Find documentation `here <https://dssg.github.io/aequitas/>`_.

Installation
============

Aequitas requires Python 3.

Install this Python library from source::

    python3 setup.py install

...or named as an installation requirement, *e.g.* via ``pip``::

    pip3 install git+https://github.com/dssg/aequitas.git

You may then import the ``aequitas`` module from Python::

    import aequitas

...or execute the auditor from the command line::

    aequitas-report

Docker
======
Build and run within a Docker container::

    docker build -t aequitas .

    docker run -p 5000:5000 -e "HOST=0.0.0.0" aequitas

Development
===========

Provision your development environment via ``develop``::

    ./develop

Common development tasks, such as deploying the webapp, may then be handled via ``manage``::

    manage --help


`Find more at the documentation  <https://dssg.github.io/aequitas/>`_.



To contact the team, please email us at [aequitas at uchicago dot edu]

----------------------------------------------
----------------------------------------------






|
|
|
|
|


© 2018 Center for Data Science and Public Policy - University of Chicago
