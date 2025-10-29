<div align="center">
🚀 Machine Learning Lab
  
🧠 Projects, Mathematical Models, & Full-Stack Implementations
  
<img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=flat&logo=python"> <img src="https://img.shields.io/badge/Jupyter-Notebook-FAE?style=flat&logo=jupyter"> <img src="https://img.shields.io/badge/License-MIT-green?style=flat">

Author: Will Hammond

Major: Physics - Math - Computer Science

Focus: Theory-driven ML, algorithmic R&D, and experimental mathematics.

</div>
📚 Repository Overview:

Hand-built neural networks, functional analysis, and ML algorithms.
Each notebook dives deep: custom architectures, physical or mathematical problem statements, bleeding-edge optimization, and rigorous benchmarking.

🗝️ Core Features
Algorithm-first: All models written from scratch or with minimal libraries for total transparency.

Physics & Math focus: Rigorous treatment of symmetry, functional equations, regression, and simulation.

Custom loss engineering: Functional constraints, boundary conditions, gradient targets.

Visualization: High-res plots, loss curves, surface mapping.

Scaling: All major projects tested locally and on M-series Apple Silicon (MPS), x86, and (optional) CUDA.

🧩 Example: Functional Equation Neural Network
![Equation](https://latex.codecogs.com

Rapidity addition law, log transforms, deep learning convergence.

python
# Custom residual loss
loss = torch.mean((f(x*y) - (f(x) + f(y)))**2)
Sampling: Uniform, boundary-biased via Beta(0.5, 0.5), stratified data for better edge-case coverage.

Architecture: 3-layer FCNN, tanh activations, cosine LR schedule, AdamW optimizer.

Results: NN output visually matches analytic curve (
log
⁡
log, 
a
r
c
t
a
n
h
arctanh, etc).

🏁 Quickstart
bash
git clone https://github.com/willhammondhimself/machine-learning.git
cd machine-learning
jupyter notebook
All dependencies listed atop each notebook. Use pip install -r requirements.txt for bulk setup.

📊 Results / Benchmarks
Learned functions: Direct overlays on analytic solutions.

Loss: Training & validation curves in log-scale.

Edge performance: Boundary sampling to expose network strengths/weaknesses.

🧠 About Me
Second-year at Pitzer College, active research in quantum cognative ML, and interests in combinatorics, trading algorithms, and mathematical optimization.

Strong fundamentals: Python, LaTeX, ML theory, proof writing, programming.
