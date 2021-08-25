# NetworkNeuroscience
Repository for scripts to run network analyses on neuroimaging data

Initial goal to establish a collection of scripts and usage for most common use-cases in the lab.

1. Network description at the group-level
  - inputs: weighted correlation matrix, other common options 
  - use-cases: determine fit to a pre-defined atlas, determine data-driven group-level modules, calculating group-level nodal metrics based on a given atlas 
    - decisions: thresholding, combining across multiple runs

2. Network description at the individual-level
  - inputs: weighted correlation matrix, other common options 
  - use-cases: determine fit to a pre-defined atlas, determine data-driven group-level modules, calculating individual-level nodal metrics based on a given atlas, deriving a reliable nodal participation coefficients at the individual level
