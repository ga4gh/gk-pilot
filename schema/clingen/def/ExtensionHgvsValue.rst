**Computational Definition**

A complex structure for sharing individual HGVS entries associated with Clinvar Variations. 

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
       *  - nucleotide
          - `Expression </ga4gh/schema/gks-common/1.x/common/json/Expression>`_
          - 0..1
          - The nucleotide HGVS expression for the variant. 
       *  - clinvarHgvsType
          - string
          - 0..1
          - The clinvar type of nucleotide expression. It must be one of the following:  'genomic, top-level', 'genomic', 'coding', or 'non-coding'.
       *  - maneSelect
          - boolean
          - 0..1
          - A boolean value indicating whether the HGVS expression is selected as the  MANE (Matched Annotation from NCBI and EMBL-EBI) Select expression.
       *  - manePlus
          - boolean
          - 0..1
          - A boolean value indicating whether the HGVS expression is selected as the  MANE Plus Clinical expression.
       *  - protein
          - `Expression </ga4gh/schema/gks-common/1.x/common/json/Expression>`_
          - 0..1
          - The protein HGVS expression for the variant.
       *  - molecularConsequence
          - `Coding </ga4gh/schema/gks-common/1.x/common/json/Coding>`_
          - 0..1
          - The molecular consequence of the variant as provided by clinvar, typically sequence ontology, SO, concepts.
