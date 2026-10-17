---
title: "Columnwise Neural Imputation"
excerpt: "Schematic diagram of COLNI<br/><img src='/images/colni.png' alt='COLNI workflow showing columnwise data splitting, neural network training, and multiple imputation.' loading='lazy'>"
collection: portfolio
---

Columnwise neural imputation (COLNI) uses a neural network with a Compensator layer and a consistent rank logits (CORAL) output layer to impute missing ordinal responses in psychological and educational assessments. Dropout and logit-space nearest-neighbor sampling generate multiple plausible completed datasets to account for imputation uncertainty.

<figure>
  <a href="{{ '/images/colni.pdf' | relative_url }}"><img src="{{ '/images/colni.png' | relative_url }}" alt="COLNI workflow showing columnwise data splitting, neural network training, and multiple imputation." width="2628" height="888" loading="lazy"></a>
  <figcaption>Schematic diagram of COLNI. Click the image to view the vector PDF.</figcaption>
</figure>

[Read the paper]({{ '/publication/2026-08-13-PM' | relative_url }}) · [Publisher page](https://doi.org/10.1037/met0000867)
