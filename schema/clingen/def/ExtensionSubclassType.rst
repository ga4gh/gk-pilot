**Computational Definition**

An extension item for the subclass type associated with a ClinVar variant.

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
          - The name of the extension item, which must be 'SubclassType'.
       *  - value
          - string
          - 0..1
          - The subclass type of the variant as provided by ClinVar. It must be one of the following: 'Genotype', 'Haplotype', or 'SimpleAllele'.
       *  - description
          - string
          - 0..1
          - 
