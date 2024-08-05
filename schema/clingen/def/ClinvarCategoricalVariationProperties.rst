**Computational Definition**

A variant in Clinvar, which may be associated with multiple statements.

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
       *  - extensions
          - :ref:`ExtensionHgvsList` | :ref:`ExtensionVariationType` | :ref:`ExtensionSubclassType` | :ref:`ExtensionChromosome` | :ref:`ExtensionCytogeneticLocation` | :ref:`ExtensionVrsProcessingErrors`
          - 0..m
          - A list of extensions to the entity. Extensions are not expected to be natively understood, but may be used for pre-negotiated exchange of message attributes between systems.
