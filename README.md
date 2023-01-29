I am Xiang CHEN, currently an AI research engineer, interested in AI for Scientific Computation. More specifically speaking:

- AI-Based Novel Solvers
    - PDE: PINN, Deep Ritz, etc.
    - Ab-Initio Simulation: FermiNet, PauliNet, DeePWF, etc.
- AI-Based Surrogate Solvers
    - PDE: FNO, DeepONet, MeshGraphNet, CFD-GCN, MP-PDE, etc.
    - Ab-Initio Simulation: Deep potential, etc.
- AI-Assisted Traditional Solvers:
    - Meshing: Meshingnet, MeshGraphNet, M2N, etc.
    - Scheme/order/stepsize control: CINN, etc.
    - Multigrid / preconditioner.
- Physics-Embedded Models:
    - Shape prior embedding (monotonicity, complexity, etc.).
    - Equivariance/invariance embedding: deepset, set trasnformer, E3NN, SchNet, etc.
    - Formulae form embedding: DeLan, LNN, Hamiltonian NN, etc.
    - Differentiable physics models
        - ODE/PDE: NeuralODE, phi-flow, jax-cfd, SU2, dolfin-adjoint, etc.
        - Optimization: OptNet, etc.
        - Fixed-Point Iteration: DEQ, etc.
        - Computational Physics/Chemistry/Material: DQC, jax-md, etc.
        - Ray-Tracing.
        - Rigid-Body Dynamics: Brax, etc.
- Inverse Design:
    - Neural reparameterization techniques.
    - Specifically designed optimization techniques.
- Applications in CEM / TCAD / mesh generation and adaptation / dynamic systems.

A literature survey on AI4PDE in Chinese is maintained [at zhihu.com](https://zhuanlan.zhihu.com/p/522145614).

A literature survey on Physics-Embedded Machine Learning in Chinese is maintained [at zhihu.com](https://zhuanlan.zhihu.com/p/574970271).

Check my [Google Scholar Homepage](https://scholar.google.com/citations?user=2cj3OTIAAAAJ&hl=zh-CN) for our work:

- M2N: Mesh Movement Networks for PDE Solvers
    - To the best of our knowledge the first learning-based end-to-end mesh movement framework that can greatly accelerate the mesh adaptation process by 3 to 4 orders of magnitude, whilst achieving comparable numerical error reduction to traditional sota methods.
- AD-NEGF: An End-to-End Differentiable Quantum Transport Simulator for Sensitivity Analysis and Inverse Problems
    - To the best of our knowledge the first end-to-end differentiable quantum transport simulator, which enables accurate and efficient calculation of differential physical quantities and solving inverse problems intractable by traditional optimization methods.
- SCGLED: Self-Consistent Gradient-Like Eigen Decomposition in Solving Schrodinger Equations
- Binet: learning to solve partial differential equations with boundary integral networks
- A neural network framework for learning Green's function
- Performance-Guaranteed ODE Solvers with Complexity-Informed Neural Networks
