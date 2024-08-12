**Computational Definition**

The GA4GH Allele Representation(AR) profile specific to Clinvar.

    **Information Model**
    
    .. list-table::
       :class: clean-wrap
       :header-rows: 1
       :align: left
       :widths: auto
       
       *  - Field
          - Type
          - Limits
          - Description
       *  - location
          - `IRI </ga4gh/schema/gks-common/1.x/data-types/json/IRI>`_ | :ref:`ClinvarSequenceLocation`
          - 0..1
          - The location of the variant.
       *  - extensions
          - :ref:`ExtensionClinvarVcf` | :ref:`ExtensionClinvarHgvsType`
          - 0..m
          - A list of extensions to the entity. Extensions are not expected to be natively understood, but may be used for pre-negotiated exchange of message attributes between systems.
