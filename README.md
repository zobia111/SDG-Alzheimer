# Single-domain generalization for Alzheimer’s detection from 3D MRIs using pseudo-morphological augmentations & contrastive learning

_Single-domain generalization for Alzheimer’s detection from 3D MRIs using pseudo-morphological augmentations & contrastive learning_

## Overview  
Deep learning–based Alzheimer’s detection from MRI scans has made great strides, but models often fail to generalize across sites with different scanners, protocols, or patient populations. In this work we tackle **single-domain generalization** (SDG): training on one dataset and testing on two unseen domains. By combining:

- **Pseudo-morphological modules** that learn anatomy-aware, class-specific 3D augmentations  
- **Supervised contrastive learning** to pull apart different representations 

we simulate realistic brain‐shape variations and learn robust, class-discriminative features.

## Key Contributions  
- **End-to-end SDG pipeline** built on a 3D U-Net backbone for Alzheimer’s detection.  
- **Learnable morphological augmentations:** 3D modules that perturb MRIs in an anatomically meaningful, class-aware way.  
- **Contrastive representation learning:** Supervised contrastive loss to enhance intra-class cohesion and inter-class separation.  
- **Cross-dataset validation:** Demonstrated improved generalization on NACC, ADNI, and AIBL, especially under class imbalance and protocol shifts.
