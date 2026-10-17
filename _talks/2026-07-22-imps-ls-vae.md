---
title: "Uncovering Residual Structure with Variational Autoencoders"
collection: talks
type: "Oral presentation"
permalink: /talks/2026-07-22-imps-ls-vae
venue: "The 2026 International Meeting of the Psychometric Society"
date: 2026-07-22
location: "Seoul, Republic of Korea"
excerpt: "Latent Space Variational Autoencoder (LS-VAE) for uncovering residual person-item interaction structure beyond primary IRT effects."
---

**Longfei Zhang**<sup>1</sup>, **Ping Chen**<sup>1,*</sup>, **Yingshi Huang**<sup>2</sup>, **Minjeong Jeon**<sup>2,*</sup>

<sup>1</sup> Collaborative Innovation Center of Assessment for Basic Education Quality, Beijing Normal University  
<sup>2</sup> School of Education and Information Studies, University of California, Los Angeles

## Abstract

Residual structure often contains valuable information about additional person-item interactions, which are not captured by standard IRT models, and it commonly manifests as violations of the conditional independence (CI) assumption (e.g., differential item functioning). In this study, we propose the Latent Space Variational Autoencoder (LS-VAE) to uncover such violations in applied settings. LS-VAE decouples residual person-item associations from the primary IRT effect and visualizes the remaining interaction structure. Specifically, it uses an encoder for fast amortized inference of respondent-specific parameters and a constrained decoder that preserves the psychometric interpretability of item parameters. On the NPI-25 dataset, LS-VAE produced an interaction map comparable to that from an MCMC-based latent-variable method, while being far more computationally efficient (well over 40x faster). It also scaled to a nearly million-observation IPIP Big Five dataset, where the learned interaction space revealed systematic method effects largely consistent with item keying. In simulation studies, LS-VAE achieved more accurate parameter recovery than baseline IRT models that ignore residual dependence. These results suggest that LS-VAE is a scalable and practical approach for diagnosing residual structure beyond primary trait dimensions, and that its interaction maps can provide informative, actionable insights for test development and subsequent analyses.

**Keywords:** variational autoencoders; latent space item response models; residual structure; conditional dependence

<sup>*</sup> *Correspondence:* Ping Chen, Beijing Normal University, No. 19, Xinjiekouwai Street, Haidian District, Beijing 100875, China (Email: [pchen@bnu.edu.cn](mailto:pchen@bnu.edu.cn)), and Minjeong Jeon, University of California, Los Angeles, Los Angeles, CA 90095, USA.

## Citation

**Zhang, L.**, Chen, P., Huang, Y., & Jeon, M. (2026, July 22). *Uncovering residual structure with variational autoencoders* [Oral presentation]. The 2026 International Meeting of the Psychometric Society, Seoul, Republic of Korea.

## Conference details

**Conference dates:** July 21-24, 2026  
**Venue:** Yonsei University, Seoul, Republic of Korea  
**Session:** Symposium: Model calibration under practical constraints  
**Presentation time:** July 22, 2026, 14:45 KST (UTC+9)  
**Room:** B126, Ballroom, The Commons

[Official conference website](https://www.psychometricsociety.org/imps-2026) · [Official program, page 27](https://www.psychometricsociety.org/sites/main/files/file-attachments/imps_2026_detailed_program.pdf?1781264536=#page=27)
