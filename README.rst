# TIPTOP

In order to be able to easily predict the AO performance, we have developed this fast algorithm producing the expected Adaptive Optics (AO see https://en.wikipedia.org/wiki/Adaptive_optics) Point Spread Function (PSF) for any of the existing AO observing modes (Single-Conjugate-AO, Laser-Tomographic-AO, Multi-Conjugate-AO, Ground-Layer-AO), and any atmospheric conditions. This TIPTOP tool takes its roots in an analytical approach, where the simulations are done in the Fourier domain. This allows to reach a very fast computation time (few seconds per PSF with GPU acceleration), and efficiently explore the wide parameter space.

## References

Reference: "TIPTOP: a new tool to efficiently predict your favorite AO PSF" SPIE 2020 (ARXIV: https://doi.org/10.48550/arXiv.2101.06486).
