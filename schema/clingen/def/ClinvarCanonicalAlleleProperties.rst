**Computational Definition**

The GA4GH Canonical Allele Representation profile specific to Clinvar.

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
       *  - definingContext
          - `IRI </ga4gh/schema/gks-common/1.x/common/json/IRI>`_ | :ref:`ClinvarAllele`
          - 0..1
          - 
       *  - members
          - `IRI </ga4gh/schema/gks-common/1.x/common/json/IRI>`_ | :ref:`ClinvarAllele`
          - 0..m
          - A non-exhaustive list of VRS variation contexts that satisfy the constraints of this categorical variant.
