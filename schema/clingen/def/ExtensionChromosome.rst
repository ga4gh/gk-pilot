**Computational Definition**

An extension item for the single chromosome associated with a Clinvar variant.

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
          - The name of the extension item, which must be 'chromosome'.
       *  - value
          - string
          - 0..1
          - The single chromosome on which the variant is located. It must be one of the following: '1', '2', '3', '4', '5', '6', '7', '8', '9', '10', '11', '12', '13', '14', '15', '16', '17', '18', '19', '20', '21', '22', 'X', 'Y', or 'MT'.
       *  - description
          - string
          - 0..1
          - 
