This folder contains my experiments with EEG analysis. Except for the section on Dynamic Causal Modeling (DCM), all experiments are based on the book Analyzing Neural Time Series Data by Mike X. Cohen.

In ERP.ipynb, I compute event-related potentials (ERPs) and create topographical plots. I also explore peaks of neural activity.

In the time-frequency analysis notebook, I test various time-frequency analysis methods, including Morlet wavelets, the filter-Hilbert transform, and short-time FFT with multitapers. Additionally, I calculate inter-trial phase clustering (ITPC) and its weighted version, wITPCz, the latter implemented using a permutation test. Most of the code is written from scratch, except for the multitaper implementation.

Finally, I perform Dynamic Causal Modeling (DCM), which is documented in detail in the corresponding folder.