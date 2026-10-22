## Matthew Helton

Ph.D. candidate in Mathematics at NYU's Courant Institute (advisor: Lai-Sang Young) and NSF Graduate Research Fellow. I build large stochastic models of cortex, and the GPU and statistical tooling that keeps them fast and correct.

Looking for a **summer 2027 research internship** in machine learning, quantitative research or scientific computing.

[matthewhelton.com](https://matthewhelton.com) · [matt.helton@nyu.edu](mailto:matt.helton@nyu.edu) · [LinkedIn](https://www.linkedin.com/in/matt-helton-8a530b99/)

### Current work

- **Spiking network model of macaque V1.** 136,000 conductance-based neurons and 36 million synapses (excitatory, PV and SOM cells, short-term plasticity), built to test how SOM interneurons shape surround suppression. Manuscript in preparation; code to be released with the paper.
- **Validated GPU acceleration.** I directed AI coding agents to optimize and port the simulator: 814 s → 183 s per simulation on one CPU core → about 40 ms on a laptop GPU, roughly 20,000× faster per simulation. Every change was gated by statistical tests against a validated reference; the GPU port matched the CPU code on all 77 per-ring readouts.
- **Bayesian calibration.** About 45 parameters fit by staged Bayesian optimization (a GPU implementation of TPE) on a validated reduced surrogate.

### Projects

| Repository | What it is |
|---|---|
| [plainclaude](https://github.com/msw1age/plainclaude) | Windows reading aid that rewrites Claude Desktop replies in plain language with a local LLM (Ollama), read from the accessibility tree. |
| [SSL_Vision](https://github.com/msw1age/SSL_Vision) | DINO self-supervised ViT-S/8 trained from scratch on 1.95M images; 6th of 39 teams (NYU Deep Learning, 2025). |
| [TD_AE](https://github.com/msw1age/TD_AE) | Time-delay autoencoder with linear (Koopman) latent dynamics for forecasting neural data; tested on Lorenz-96 and widefield imaging. |
| [LND_notebooks](https://github.com/msw1age/LND_notebooks) | Dynamic mode decomposition (exact, optimized, multiresolution and Hankel DMD) of mouse widefield and Neuropixels recordings. |
| [V1](https://github.com/msw1age/V1) | Early 400-neuron Numba prototype of the V1 model, with a neural-network surrogate for parameter search. |

### Tools

Python (PyTorch, NumPy, SciPy, Numba, scikit-learn, pandas) · GPU simulation · Bayesian optimization · statistical testing · SQL · Git · LaTeX
