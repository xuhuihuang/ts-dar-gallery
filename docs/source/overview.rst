TS-DAR Overview
==============

Abstract
--------
Identifying transitional states is crucial for understanding protein conformational changes that underlie numerous biological processes. Markov state models (MSMs), built from Molecular Dynamics (MD) simulations, capture these dynamics through transitions among metastable conformational states, and have demonstrated success in studying protein conformational changes. However, MSMs face challenges in identifying transition states, as they partition MD conformations into discrete metastable states (or free energy minima), lacking description of transition states located at the free energy barriers. Here, we introduce Transition State identification via Dispersion and vAriational principle Regularized neural networks (TS-DAR), a deep learning framework inspired by out-of-distribution (OOD) detection in trustworthy artificial intelligence (AI). TS-DAR offers an end-to-end pipeline that can simultaneously detect all transition states between multiple free minima from MD simulations using the regularized hyperspherical embeddings in latent space. The key insight of TS-DAR lies in treating transition state structures as OOD data, recognizing that they are sparsely populated and exhibit a distributional shift from metastable states. We demonstrate the power of TS-DAR by applying it to a 2D potential, alanine dipeptide, and the translocation of a DNA motor protein on DNA, where it outperforms previous methods in identifying transition states.

Link to TS-DAR GitHub: https://github.com/xuhuihuang/ts-dar

Citation: Liu, B.; Boysen, J. G.; Unarta, I. C.; Du, X.; Li, Y.; Huang, X. Exploring Transition States of Protein Conformational Changes via Out-of-Distribution Detection in the Hyperspherical Latent Space. Nat Commun 2025, 16, 349. https://doi.org/10.1038/s41467-024-55228-4.


Tutorial
--------

Link to tutorial GitHub: https://github.com/xuhuihuang/ts-dar-tutorials

Tutorial Citation: Goonetilleke, E. C.; Liu, B.; Wu, Y.; O’Connor, M. S.; Huang, X. A Practical Guide to Transition State Analysis in Biomolecular Simulations with TS-DAR. J. Phys. Chem. B 2025, 129 (47), 12133–12145. https://doi.org/10.1021/acs.jpcb.5c06097.
 
