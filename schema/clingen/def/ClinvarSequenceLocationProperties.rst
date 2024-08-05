**Computational Definition**

The GA4GH Sequence Location Representation(SL) profile specific to Clinvar.

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
       *  - sequenceReference
          - `IRI </ga4gh/schema/gks-common/1.x/common/json/IRI>`_ | :ref:`ClinvarSequenceReference`
          - 0..1
          - The reference sequence for the location.
       *  - extensions
          - None
          - 0..1
          - 
