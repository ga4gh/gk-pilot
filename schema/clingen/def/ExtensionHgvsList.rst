**Computational Definition**

An extension item for a list of HGVS values associated with a Clinvar variant.

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
       *  - name
          - string
          - 0..1
          - The name of the extension item, which must be 'hgvsList'.
       *  - value
          - :ref:`ExtensionHgvsValue`
          - 0..m
          - A list of HGVS values associated with the Clinvar variant.
       *  - description
          - string
          - 0..1
          - 
