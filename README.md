# Normalizing Flows (Autoregressive + Coupling) for Generative Modeling
![GitHub last commit](https://img.shields.io/github/last-commit/elliothha/normalizing-flows) ![GitHub repo size](https://img.shields.io/github/repo-size/elliothha/normalizing-flows)

*[3/16/24 Update] Uploaded current work on Norm Flows, training won't converge still*

This repo contains PyTorch implementations of various Autoregressive and Coupling Normalizing Flow models for generative modeling on the MNIST dataset. As of 3/16/24, training still won't converge for inference though, work in progress.

Full generative modeling zoo found [here](https://github.com/elliothha/generative-modeling-zoo).

by **Elliot H Ha**. Duke University

[elliothha.tech](https://elliothha.tech/) | [elliot.ha@duke.edu](mailto:elliot.ha@duke.edu)

---

## Dependencies
- Jupyter Notebook
- PyTorch

## Project Structure
`models/` is the main folder containing the Jupyter Notebook file implementing the Normalizing Flow models for the MNIST dataset.

Future work for this repo includes turning the Notebook into a modularized Python repo and further abstract the various flow models for a clearer and more concise implementation.

Also, obviously, I still need to get the flow models to actually converge. Haha.

## Hyperparameters & Architecture
Work in progress

### Real NVP

### NICE

### IAF

### MAF

### Glow

## Normalizing Flow Generated Sample Results
Work in progress

---

## References
1. Real NVP -- *Density estimation using Real NVP*, Dinh et al. 2016 | [1605.08803](https://arxiv.org/abs/1605.08803)
2. NICE -- *Non-linear Independent Components Estimation*, Dinh et al. 2014 | [1410.8516](https://arxiv.org/abs/1410.8516)
3. IAF -- *Improved Variational Inference with Inverse Autoregressive Flow*, Kingma et al. 2016 | [1606.04934](https://arxiv.org/abs/1606.04934)
4. MAF -- *Masked Autoregressive Flow for Density Estimation*, Papamakarios et al. 2017 | [1705.07057](https://arxiv.org/abs/1705.07057)
5. Glow -- *Generative Flow with Invertible 1x1 Convolutions*, Kingma and Dhariwal 2018 | [1807.03039](https://arxiv.org/abs/1807.03039)
6. MADE -- *Masked Autoencoder for Distribution Estimation*, Germain et al. 2015 | [1502.03509](https://arxiv.org/abs/1502.03509)
7. Eric Jang's blogpost tutorials on Normalizing Flows | [link](https://blog.evjang.com/2018/01/nf1.html)
8. Eric Jang's GitHub | [link](https://github.com/ericjang/normalizing-flows-tutorial/)
9. Andrej Kaparthy's GitHub | [link](https://github.com/karpathy/pytorch-normalizing-flows/blob/master/nflib/flows.py)

DEAR GOD IF I EVER GET TRAINING TO CONVERGE it will be a miracle. But genuinely speaking, each resource is so useful when it comes to Normalizing Flows. See Eric Jang's blogpost for intuition. See Kaparthy's GitHub for implementation. I liked the MAF paper a lot, but didn't really like the IAF one. Still a work in progress though.
