---
title: "UMPIRE-Net: Unrolled Magnitude–Phase Regularization Network for Accelerated MRI"
date: 2026-01-01 00:01:00 +0000
selected: true

pub: "IEEE International Workshop on Machine Learning for Signal Processing (MLSP)"
pub_post: "Accepted"

pub_date: "2026"

abstract: >
  MRI reconstruction from undersampled k-space measurements is an ill-posed inverse problem. Physics-driven deep learning (PD-DL) methods have shown strong performance for this task by combining the MRI forward model with learned image regularization within algorithm-unrolling frameworks. However, most existing PD-DL methods reconstruct complex-valued images directly, thereby implicitly coupling magnitude and phase within a single learned representation. This coupled regularization may be suboptimal in reconstruction settings where accurate phase modeling plays an important role, such as partial Fourier (PF) imaging, where recovery of the omitted asymmetric k-space measurements depends on the underlying image phase. In such scenarios, explicit modeling of magnitude and phase as separate components may reduce the reliance on externally estimated or predefined phase information. To this end, we propose UMPIRE-Net (Unrolled Magnitude-Phase In REgularization Network), a PD-DL method that introduces separate learned regularizers for magnitude and phase components, together with a novel data-fidelity formulation that enforces measurements consistency. We evaluate UMPIRE-Net for accelerated MRI with PF across different datasets and acceleration factors. Experimental results demonstrate that our proposed method improves reconstruction quality compared with a conventional complex-valued PD-DL baseline, yielding sharper images and reduced artifacts. 


authors:
  - Mahdi Saberi
  - Toygan Kiliç
  - Mehmet Akçakaya

links:
  Paper: "#"
---
