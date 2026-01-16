Supporting Tools
!!!!!!!!!!!!!!!!
.. note:: These tools assist in the curation and representation of gene fusion data. To do this,
   they must choose conventions that are not defined in this specification, specifically around
   data exchange. For example, these implementations choose to use `SequenceLocation`_ from the
   Global Alliance for Genomics and Health (GA4GH) `Variation Representation Specification (VRS)`_,
   due to its use of inter-residue coordinates and extensible design. Other implementations may choose
   different conventions for representation of gene fusion data in system exchange.

.. _Variation Representation Specification (VRS): https://vrs.ga4gh.org/en/2.0

FUSOR
@@@@@

The **FUSOR** data validation / translation Python package provides data classes and constructor tools to create valid
gene fusion messages for use in downstream applications. The package is publicly available on the Python Package Index
(PyPI).

- `PyPI package <https://pypi.org/project/fusor>`_
- `Source code <https://github.com/cancervariants/fusor>`_

.. _fusion-curation-tool:

Fusion-Builder
@@@@@@@@@@@@@@

The **Fusion-Builder** platform provides a user interface to curate valid gene fusion objects. This tool demonstrates
the computable structure and associated nomenclature for gene fusions.

- `Webtool <https://fusion-builder.cancervariants.org>`_
- `Source code <https://github.com/cancervariants/fusion-builder/>`_
