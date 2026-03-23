# When Lines Meet Textures: Spatial-Frequency Aligned Diffusion Features for Cross-Sparsity Correspondence


### 📢 News
- **[2026-03]** 🚀 The code and pre-trained models will be released soon. Please star 🌟 this repo for updates!
- **[2026-02]** 🎉 This paper has been accepted to **CVPR 2026**!

### 📝 Abstract

Establishing accurate correspondence between sparse
line representations and rich textured imagery remains a
formidable challenge. While diffusion features excel in se-
mantic correspondence, they struggle to bridge the fun-
damental gap between abstract sketches and texture-rich
photographs. We identify two critical disparities: spa-
tial domain misalignment from structural abstraction dif-
ferences, and frequency domain inconsistencies from tex-
ture density variations. Based on this analysis, we propose
SFA-DIFT, a novel approach that learns spatial-frequency
aligned diffusion features for robust cross-modal corre-
spondence. Unlike previous methods focusing solely on spa-
tial alignment, our key innovation performs dual-domain
alignment by learning unified clean diffusion features while
strategically aggregating low-frequency components in the
frequency domain. This comprehensive spatial-frequency
alignment enables equitable understanding between sparse
abstractions and rich textures. To validate our approach,
we extend the existing sketch-photo correspondence dataset
(PSC6K) by generating multi-style textured imagery, cre-
ating MS-PSC6K, a comprehensive correspondence bench-
mark. Extensive experiments demonstrate that SFA-DIFT
achieves state-of-the-art performance, delivering substan-
tial improvements with an average of 0.87% on PCK@1,
2.20% on PCK@5, and 0.95% on PCK@10 over previous
best methods, validating the effectiveness and robustness of
our dual-domain alignment approach


### 📅 Roadmap

We are currently organizing the code and will release it in the following order:

- Inference / Demo scripts (for correspondence visualization)
- Pre-trained weights (SF-DIFT adapters)
- Evaluation code on standard benchmarks
- Training scripts
