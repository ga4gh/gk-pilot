**Computational Definition**

An extension item for the cytogenetic location associated with a ClinVar variant.

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
          - The name of the extension item, which must be 'CytogeneticLocation'.
       *  - value
          - string
          - 0..1
          - The cytogenetic location of the variant as provided by ClinVar.
       *  - description
          - string
          - 0..1
          - 
