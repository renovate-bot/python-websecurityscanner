.. include:: README.rst

.. include:: multiprocessing.rst

API Reference
-------------
This package includes clients for multiple versions of the Web Security Scanner API. By default, you will get ``v1``, the latest version.

.. toctree::
    :maxdepth: 2

    websecurityscanner_v1/services
    websecurityscanner_v1/types

The previous releases spelled ``v1beta`` and ``v1alpha`` are provided to continue to support code previously written against it. In order to use it, you will want to import from it e.g., ``google.cloud.websecurityscanner_v1alpha`` in lieu of ``google.cloud.websecurityscanner`` (or the equivalent ``google.cloud.websecurityscanner_v1``).


v1beta
~~~~~~~
.. toctree::
    :maxdepth: 2

    websecurityscanner_v1beta/services
    websecurityscanner_v1beta/types


v1alpha
~~~~~~~
.. toctree::
    :maxdepth: 2

    websecurityscanner_v1alpha/services
    websecurityscanner_v1alpha/types


Migration Guide
---------------

See the guide below for instructions on migrating to the 1.x release of this library.

.. toctree::
    :maxdepth: 2

    UPGRADING


Changelog
---------

For a list of all ``google-cloud-websecurityscanner`` releases.

.. toctree::
    :maxdepth: 2

    changelog
