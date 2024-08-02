**Computational Definition**

An extension item for the variation type associated with a ClinVar variant.

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
          - The name of the extension item, which must be 'VariationType'.
       *  - value
          - string
          - 0..1
          - The type of variant as provided by ClinVar. It must be one of the following: 'Complex', 'CompoundHeterozygote', 'copy number gain', 'copy number loss', 'Deletion', 'Diplotype', 'Distinct chromosomes', 'Duplication', 'fusion', 'Haplotype, single variant', 'Haplotype', 'Indel', 'Insertion', 'Inversion', 'Microsatellite', 'Phase unknown', 'protein only', 'single nucleotide variant', 'Tandem duplication', 'Translocation', or 'Variation'.
       *  - description
          - string
          - 0..1
          - 
