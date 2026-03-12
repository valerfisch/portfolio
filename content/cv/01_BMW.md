---
catch_phrase: "Deep learning surrogate models for physical system simulation"
position: Research Engineer, Vehicle Dynamics AI (Master's Thesis)
start_date: 2024
end_date: 2025
company: BMW Group
link: https://www.bmw.de/de/home.html
condensed: Designed and deployed deep learning surrogate models (Transformers, GANs, Encoder-Decoders) to replace physical simulation in vehicle dynamics, with custom loss functions and modular training pipelines in Python/PyTorch.
professional: true
educational: false
award: false
parent: CV
tags:
  - Python
  - PyTorch
  - NumPy
  - Pandas
  - Matplotlib
  - Docker
  - Git
---

At BMW Group's research and innovation center, I developed AI-based surrogate models to replace traditional physical simulations of auxiliary spring behavior in vehicle dynamics.

### What I built
- End-to-end ML pipeline in Python/PyTorch: data generation, model training, evaluation, and inference
- Evaluated 4 architectures (Transformer, FCNN, cGAN, Encoder-Decoder) for characteristic curve prediction
- Designed custom loss functions (Curvature-Informed, Physics-Informed) tailored to domain constraints
- Deployed the production model into BMW's existing C++ simulation toolchain

### Impact
- Encoder-Decoder achieved best real-world performance (MSE 0.0011); custom loss improved Transformer test loss by 61.6%
- Enabled faster simulation workflows during early vehicle development stages
- Collaborated across 3 engineering teams to ensure legacy system compatibility and reproducibility