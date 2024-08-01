**Computational Definition**

Quality measures associated with the gnomAD CohortAlleleFrequency and how it was derived, which may impact interpretation.

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
       *  - meanDepth
          - number
          - 0..1
          - The mean depth of coverage.
       *  - fractionCoverage20x
          - number
          - 0..1
          - The fraction of individuals with at least 20x coverage.
       *  - qcFilters
          - string
          - 0..m
          - 
       *  - monoallelic
          - boolean
          - 0..1
          - All samples are homozygous alternate for the variant.
       *  - lowComplexityRegion
          - boolean
          - 0..1
          - This flag indicates the variant is found in a low complexity  region. These regions were identified with the symmetric DUST algorithm at a score threshold of 30.
       *  - lowConfidenceLossOfFunctionError
          - boolean
          - 0..1
          - Low confidence in predicted Loss of Function (pLoF), where  variant is determined by LOFTEE to be unlikely loss of function for a transcript.
       *  - lossOfFunctionWarning
          - boolean
          - 0..1
          - A warning provided by LOFTEE to use caution when interpreting  the transcript or variant.
       *  - noncodingTranscriptError
          - boolean
          - 0..1
          - Marked in a putative loss of function category by VEP  (essential splice, stop-gained, or frameshift) but appears on a non-protein-coding transcript.
       *  - heterozygousSkewedAlleleCount
          - integer
          - 0..1
          - The count of individuals called as heterozygous for this variant  with a skewed allele balance, indicating some of these individuals  may be miscalled homozygous alternative allele.
