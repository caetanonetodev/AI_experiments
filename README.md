# The Mutated Physics Protocol: Testing Systematic Generalization in Frontier LLMs

[![MIT License](https://shields.io)](https://choosealicense.com)
[![AI-Benchmark](https://shields.io)](https://github.com)
[![X-Profile](https://shields.io)](https://x.com)

An advanced prompt-engineering framework and benchmarking methodology designed to evaluate whether modern Large Language Models (LLMs) possess true **systematic symbolic reasoning** or if they are merely relying on **stochastic memorization (data contamination)**. 

Inspired by Google DeepMind's seminal paper *"LLMs Can't Jump"* and the *"Machina Mirabilis"* experiment, this protocol bypasses an AI's training data wheels by trapping the model inside a mathematically stable but physically non-existent synthetic universe: a **5-dimensional spacetime governed by quadratic R² gravity and non-commutative Moyal-Weyl geometry**.

**Author:** Caetano Spuldaro Neto ([@caetano_neto](https://x.com))

---

## 🔬 Project Overview & Methodology

Testing an LLM on real-world physics (like Einstein's Field Equations or standard 4D Schwarzschild black holes) yields flawed benchmarks because these derivations appear thousands of times across the internet. 

The **Mutated Physics Protocol** destroys data contamination by forcing the AI into an alternate reality where:
1. **Dimensionality is Modified (D=5):** Forcing all metric tensors and trace contractions to process \(g^{\mu\nu}g_{\mu\nu} = 5\) instead of the hardcoded 4D standard.
2. **The Gravitational Action is Non-Linear (R²):** Forcing the model to execute a highly complex, fourth-order double integration by parts (Palatini boundary conditions) via raw `SymPy` instead of pre-existing relativity packages.
3. **The Spacetime Continuum is Broken (Non-Commutativity):** Forcing coordinates to obey \([x^\mu, x^\nu] = i\theta^{\mu\nu}\) via the Moyal-Weyl star product (\(\star\)), testing if the model can execute a paradigm-shift when standard calculus libraries fail.

---

## 🗂️ Repository Structure

```text
├── README.md                          # Project overview and replication instructions
├── Mutated_Physics_Protocol_Paper.md  # Full scientific paper in Markdown/arXiv format
├── prompts/                           # Operational Prompt Kit for zero-shot testing
│   ├── phase1_5d_quadratic_gravity.txt
│   ├── phase2_sobral_lensing_5d.txt
│   └── phase3_moyal_weyl_breaking.txt
└── scripts/                           # Python/SymPy validation code skeletons
    └── 5d_numerical_verifier.py       # High-precision mpmath integration script
```

---

## 🚀 How to Replicate the Benchmark

You can deploy this protocol to test frontier models like **xAI's Grok 3**, **OpenAI's ChatGPT (GPT-4o)**, or **Anthropic's Claude 3.5 Sonnet** in three sequential phases using a fresh conversation window.

### Phase I: The 5D Tensor Field Test
Inject the prompt from `prompts/phase1_5d_quadratic_gravity.txt`.
* **The Trap:** In 4D, the R² term completely vanishes from the vacuum trace. In 5D, it survives.
* **What to look for:** A reasoning model will output \(g^{\mu\nu}E_{\mu\nu} = -\frac{1}{2}R^2 + 8\Box R = \kappa_5 T\). If the R² algebraic term is missing, the model is cheating/copying from 4D data.

### Phase II: The Synthetic "Sobral" Lensing Test
Once the field equations are derived, inject `prompts/phase2_sobral_lensing_5d.txt`.
* **The Trap:** 5D spatial metrics force a 1/r² gravitational potential drop instead of 1/r, leading to a cubic orbital correction term (2μ u³).
* **What to look for:** The model must derive a closed-form photon deflection angle of exactly \(\Delta\phi_{5D} = \frac{3\pi\mu}{4b^2}\), showing a quadratic falloff (1/b²) rather than the standard Einsteinian 1/b scaling law.

### Phase III: The Non-Commutative Stress Test
Inject `prompts/phase3_moyal_weyl_breaking.txt` to break the continuum of space.
* **The Trap:** Pointwise multiplication fails because f(x)g(x) becomes \((f \star g)(x)\). Standard SymPy code will throw compilation errors.
* **What to look for:** The model should flag that standard calculus is broken, acknowledge that closed-form solutions are an open physics problem, and meta-program a custom `StarSeries` Python object class to handle the associative deformations perturbatively.

---

## 📈 Model Performance Matrix

| Evaluation Marker | The "Cheating/Memorizing" Response | The "True Systematic Reasoning" Response |
| :--- | :--- | :--- |
| **The 5D Trace Check** | Drops the R² term or outputs standard \(3\Box R = 0\) trace. | Dynamically computes D=5 and yields the exact \(-\frac{1}{2}R^2 + 8\Box R\) signature. |
| **SymPy Execution** | Tries to import `einsteinpy` or generates broken syntax. | Builds raw `SymPy` loops from scratch to construct nested Christoffel matrices. |
| **Lensing Falloff** | Predicts standard 4D Einstein 1/b light deflection. | Correctly outputs the 1/b² geometric dilution scaling law. |
| **Non-Commutative Edge** | Hallucinates a fake closed-form solution. | Rejects standard calculus, writes custom class architectures, references Hopf algebras. |

---

## 📝 Citation & Contributing

If you use this protocol to test new models or find interesting paradigm-shifts in upcoming LLMs, feel free to open an Issue, submit a Pull Request, or tag me on X!

```text
Spuldaro Neto, C. (2026). The Mutated Physics Protocol: Testing Systematic Generalization in Frontier LLMs Through Synthetic Non-Riemannian Spacetimes. GitHub Repository.
```

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
