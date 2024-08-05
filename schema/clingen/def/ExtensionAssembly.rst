**Computational Definition**

An extension item for the assembly associated with a Clinvar variant.

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
          - The name of the extension item, which must be 'assembly'.
       *  - value
          - string
          - 0..1
          - The assembly of the variant as provided by Clinvar. It must be one of the following: 'GRCh37', 'GRCh38', or 'NCBI36'.
       *  - description
          - string
          - 0..1
          - 
