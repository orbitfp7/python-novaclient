Python bindings to the OpenStack Nova API
=========================================

This is a client for OpenStack Nova API. There's :doc:`a Python API
<api>` (the :mod:`novaclient` module), and a :doc:`command-line script
<shell>` (installed as :program:`nova`). Each implements the entire
OpenStack Nova API.

You'll need credentials for an OpenStack cloud that implements the
Compute API, such as TryStack, HP, or Rackspace, in order to use the nova client.

.. seealso::

    You may want to read the `OpenStack Compute Developer Guide`__  -- the overview, at
    least -- to get an idea of the concepts. By understanding the concepts
    this library should make more sense.

    __ http://docs.openstack.org/api/openstack-compute/2/content/

Contents:

.. toctree::
   :maxdepth: 2

   shell
   api
   ref/index
   ref/v2/index
   releases

Contributing
============

Code is hosted at `git.openstack.org`_. Submit bugs to the Nova project on
`Launchpad`_. Submit code to the openstack/python-novaclient project using
`Gerrit`_.

.. _git.openstack.org: https://git.openstack.org/cgit/openstack/python-novaclient
.. _Launchpad: https://launchpad.net/nova
.. _Gerrit: http://docs.openstack.org/infra/manual/developers.html#development-workflow

Testing
-------

The preferred way to run the unit tests is using ``tox``.

See `Consistent Testing Interface`_ for more details.

.. _Consistent Testing Interface: http://git.openstack.org/cgit/openstack/governance/tree/reference/project-testing-interface.rst

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
