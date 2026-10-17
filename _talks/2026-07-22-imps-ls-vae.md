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

**Longfei Zhang**<sup>1</sup>, **Ping Chen**<sup>1</sup>, **Yingshi Huang**<sup>2</sup>, **Minjeong Jeon**<sup>2</sup>

<sup>1</sup> Collaborative Innovation Center of Assessment for Basic Education Quality, Beijing Normal University  
<sup>2</sup> School of Education and Information Studies, University of California, Los Angeles

## Abstract

Residual structure often contains valuable information about additional person-item interactions, which are not captured by standard IRT models, and it commonly manifests as violations of the conditional independence (CI) assumption (e.g., differential item functioning). In this study, we propose the Latent Space Variational Autoencoder (LS-VAE) to uncover such violations in applied settings. LS-VAE decouples residual person-item associations from the primary IRT effect and visualizes the remaining interaction structure. Specifically, it uses an encoder for fast amortized inference of respondent-specific parameters and a constrained decoder that preserves the psychometric interpretability of item parameters. On the NPI-25 dataset, LS-VAE produced an interaction map comparable to that from an MCMC-based latent-variable method, while being far more computationally efficient (well over 40x faster). It also scaled to a nearly million-observation IPIP Big Five dataset, where the learned interaction space revealed systematic method effects largely consistent with item keying. In simulation studies, LS-VAE achieved more accurate parameter recovery than baseline IRT models that ignore residual dependence. These results suggest that LS-VAE is a scalable and practical approach for diagnosing residual structure beyond primary trait dimensions, and that its interaction maps can provide informative, actionable insights for test development and subsequent analyses.

## Citation

**Zhang, L.**, Chen, P., Huang, Y., & Jeon, M. (2026, July 22). *Uncovering residual structure with variational autoencoders* [Oral presentation]. The 2026 International Meeting of the Psychometric Society, Seoul, Republic of Korea.
