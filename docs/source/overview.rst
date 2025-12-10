TS-DAR Overview
==============

Abstract
--------
Identifying transitional states is crucial for understanding protein conformational changes that underlie numerous biological processes. Markov state models (MSMs), built from Molecular Dynamics (MD) simulations, capture these dynamics through transitions among metastable conformational states, and have demonstrated success in studying protein conformational changes. However, MSMs face challenges in identifying transition states, as they partition MD conformations into discrete metastable states (or free energy minima), lacking description of transition states located at the free energy barriers. Here, we introduce Transition State identification via Dispersion and vAriational principle Regularized neural networks (TS-DAR), a deep learning framework inspired by out-of-distribution (OOD) detection in trustworthy artificial intelligence (AI). TS-DAR offers an end-to-end pipeline that can simultaneously detect all transition states between multiple free minima from MD simulations using the regularized hyperspherical embeddings in latent space. The key insight of TS-DAR lies in treating transition state structures as OOD data, recognizing that they are sparsely populated and exhibit a distributional shift from metastable states. We demonstrate the power of TS-DAR by applying it to a 2D potential, alanine dipeptide, and the translocation of a DNA motor protein on DNA, where it outperforms previous methods in identifying transition states.

Link to TS-DAR GitHub: https://github.com/xuhuihuang/ts-dar

Tutorial
--------

Link to tutorial GitHub: https://github.com/xuhuihuang/ts-dar-tutorials
