================
Virtual Packages
================

Conda allows for the registering of virtual packages in the index data via
the plugin system. This mechanism lets users write plugins that provide
version identification for proprieties only known at runtime (e.g., OS
information).

.. autoclass:: conda.models.plugins.CondaVirtualPackage
   :members:
   :undoc-members:

.. autofunction:: conda.plugins.hookspec.CondaSpecs.conda_virtual_packages
