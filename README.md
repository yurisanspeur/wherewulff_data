# WhereWulff Data
This repository houses electronic structure data and metadata generated as part of the case study in "WhereWulff: A semi-autonomous workflow for systematic catalyst surface reactivity under reaction conditions" 

# Data organization
The data is partitioned across three main root folders:
 - Bulk Workflow (bulk_wf)
    - Material Composition e.g. BaSnTiO
       - NM
       - AFM
       - FM      
 - WhereWulff (wherewulff)
    - Material Composition and Miller Index e.g. BaSnTiO-001
      - Surface Energy
      - Surface Pourbaix
      - OER
 - Convergence Tests (convergence)
    - Type of setting e.g. encut, kpoints, slab thickness
    
    
# Citing `WhereWulff`

If you use this codebase in your work, please consider citing:

```bibtex
@article{wherewulff2023,
title = {WhereWulff: A semi-autonomous workflow for systematic catalyst surface reactivity under reaction conditions},
author = {Rohan Yuri Sanspeur, Javier Heras-Domingo, John R. Kitchin and Zachary Ulissi},
journal = {in preparation},
year = {2023},
}
```
