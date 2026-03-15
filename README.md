# 📊 Probability for Engineers

**Haydar Kilic · Artificial Intelligence Engineering**

This repository contains interactive Jupyter Notebook materials for the **Probability for Engineers** course. Each lecture is presented as a self-contained notebook consisting of theoretical background, Python implementations, visualizations, and exercises.

---

## 📚 Course Contents

| # | Notebook | Topics | Key Concepts |
|---|----------|--------|--------------|
| 1 | `Probability_Chapter1_Kombinatoryal_Analiz.ipynb` | Basic Counting Principle, Permutations, Combinations, Multinomial Coefficients | $n!$, $P(n,r)$, $\binom{n}{r}$, multinomial theorem |
| 2 | `Probability_Chapter2_Olasilik_Aksiyomlari.ipynb` | Sample Space and Events, Set Operations, DeMorgan's Laws, Kolmogorov Axioms, Inclusion-Exclusion, Birthday Problem | $P(A)$, $A^c$, $A \cup B$, $A \cap B$ |
| 3 | `Probability_Chapter3_Kosullu_Olasilik.ipynb` | Conditional Probability, Multiplication Rule, Law of Total Probability, Bayes' Theorem, Independent Events, Mutual Independence | $P(A \mid B)$, $P(A \cap B)$, Bayes |
| 4 | `Probability_Chapter4_Kesikli_Rasgele_Degiskenler.ipynb` | Random Variable Definition, CDF, PMF, Expected Value, Variance, Bernoulli, Binomial, Poisson, Geometric, Negative Binomial | $E[X]$, $\text{Var}(X)$, $\text{Bin}(n,p)$, $\text{Poi}(\lambda)$ |
| 5 | `Probability_Chapter5_Surekli_Rastgele_Degiskenler.ipynb` | PDF, CDF, Expected Value and Variance, Uniform Distribution, Normal Distribution, z-Transform, Binomial Approximation, Distribution of a Function | $f(x)$, $F(x)$, $\mathcal{N}(\mu, \sigma^2)$, $z$-score |
| 6 | `Probability_Chapter6_BirlikteDagilimliRD.ipynb` | Joint CDF, Discrete/Continuous Joint Distributions, Marginal and Conditional Distributions, Independent RVs, Convolution | $F_{X,Y}(x,y)$, $f_{X \mid Y}$, convolution |
| 7 | `Probability_Chapter7_Beklenen_Deger_Ozellikleri.ipynb` | Expectation of $g(X,Y)$, Linearity of Expectation, Product Expectation, Covariance, Correlation, Conditional Expectation, Conditional Variance, Moment Generating Functions | $E[XY]$, $\text{Cov}(X,Y)$, $\rho$, MGF |

---

## 🗂️ Repository Structure

```
probability/
│
├── README.md
├── requirements.txt
│
├── Probability_Chapter1_Kombinatoryal_Analiz.ipynb
├── Probability_Chapter2_Olasilik_Aksiyomlari.ipynb
├── Probability_Chapter3_Kosullu_Olasilik.ipynb
├── Probability_Chapter4_Kesikli_Rasgele_Degiskenler.ipynb
├── Probability_Chapter5_Surekli_Rastgele_Degiskenler.ipynb
├── Probability_Chapter6_BirlikteDagilimliRD.ipynb
└── Probability_Chapter7_Beklenen_Deger_Ozellikleri.ipynb
```

---

## ⚙️ Setup and Usage

### Requirements

- Python 3.10 or higher
- JupyterLab or Jupyter Notebook

### Environment Setup

```bash
# Clone the repository
git clone https://github.com/HAYDARKILIC/probability.git
cd probability

# Create a virtual environment (recommended)
python -m venv .venv
source .venv/bin/activate        # Linux / macOS
# .venv\Scripts\activate         # Windows

# Install dependencies
pip install -r requirements.txt

# Launch JupyterLab
jupyter lab
```

---


## 📦 Libraries Used

| Library | Purpose |
|---------|---------|
| `numpy` | Numerical computation, array operations |
| `scipy` | Statistical distributions, special functions |
| `sympy` | Symbolic mathematics, derivative/integral validation |
| `matplotlib` | Plotting and visualization |
| `itertools` | Combinatorial generation (permutations, combinations) |
| `collections` | Frequency counting (`Counter`) |

---

*Haydar Kilic, Artificial Intelligence Engineering*