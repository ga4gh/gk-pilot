**Computational Definition**

An extension item for the Clinvar HGVS type associated with a Clinvar variant.

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
          - The name of the extension item, which must be 'clinvarHgvsType'.
       *  - value
          - string
          - 0..1
          - The Clinvar HGVS type associated with the Clinvar variant. It must be one of the following: 'genomic, top-level', 'genomic', 'coding', or 'non-coding'.
       *  - description
          - string
          - 0..1
          - 
