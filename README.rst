Python Client for Cloud Shell
=============================

|ga| |pypi| |versions|

`Cloud Shell`_: is an interactive shell environment for Google Cloud that makes it easy 
for you to learn and experiment with Google Cloud and manage your projects and resources 
from your web browser.

- `Client Library Documentation`_
- `Product Documentation`_

.. |ga| image:: https://img.shields.io/badge/support-ga-gold.svg
   :target: https://github.com/googleapis/google-cloud-python/blob/main/README.rst#ga-support
.. |pypi| image:: https://img.shields.io/pypi/v/google-cloud-shell.svg
   :target: https://pypi.org/project/google-cloud-shell/
.. |versions| image:: https://img.shields.io/pypi/pyversions/google-cloud-shell.svg
   :target: https://pypi.org/project/google-cloud-shell/
.. _Cloud Shell: https://cloud.google.com/shell
.. _Client Library Documentation: https://cloud.google.com/python/docs/reference/cloudshell/latest
.. _Product Documentation:  https://cloud.google.com/shell/docs

Quick Start
-----------

In order to use this library, you first need to go through the following steps:

1. `Select or create a Cloud Platform project.`_
2. `Enable billing for your project.`_
3. `Setup Authentication.`_

.. _Select or create a Cloud Platform project.: https://console.cloud.google.com/project
.. _Enable billing for your project.: https://cloud.google.com/billing/docs/how-to/modify-project#enable_billing_for_a_project
.. _Setup Authentication.: https://googleapis.dev/python/google-api-core/latest/auth.html

Installation
~~~~~~~~~~~~

Install this library in a `virtualenv`_ using pip. `virtualenv`_ is a tool to
create isolated Python environments. The basic problem it addresses is one of
dependencies and versions, and indirectly permissions.

With `virtualenv`_, it's possible to install this library without needing system
install permissions, and without clashing with the installed system
dependencies.

.. _`virtualenv`: https://virtualenv.pypa.io/en/latest/


Mac/Linux
^^^^^^^^^

.. code-block:: console

    pip install virtualenv
    virtualenv <your-env>
    source <your-env>/bin/activate
    <your-env>/bin/pip install google-cloud-shell


Windows
^^^^^^^

.. code-block:: console

    pip install virtualenv
    virtualenv <your-env>
    <your-env>\Scripts\activate
    <your-env>\Scripts\pip.exe install google-cloud-shell

Next Steps
~~~~~~~~~~

-  Read the `Client Library Documentation`_ for Cloud Shell
   to see other available methods on the client.
-  Read the `Cloud Shell Product documentation`_ to learn
   more about the product and see How-to Guides.
-  View this `README`_ to see the full list of Cloud
   APIs that we cover.

.. _Cloud Shell Product documentation:  https://cloud.google.com/shell/docs
.. _README: https://github.com/googleapis/google-cloud-python/blob/main/README.rst