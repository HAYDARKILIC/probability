# 📊 Probability for Engineers

**Haydar Kilic · Artificial Intelligence Engineering**

This repository contains interactive Jupyter Notebook materials for the **Probability for Engineers** course. Each lecture is presented as a self-contained notebook consisting of theoretical background, Python implementations, visualizations, and exercises.

---

## 📚 Course Contents

| # | Notebook | Topics | Key Concepts |
|---|----------|--------|--------------|
| 1 | `Bolum1_Kombinatoryal_Analiz.ipynb` | Basic Counting Principle, Permutations, Combinations, Multinomial Coefficients | $n!$, $P(n,r)$, $\binom{n}{r}$, multinomial theorem |
| 2 | `Bolum2_Olasilik_Aksiyomlari.ipynb` | Sample Space and Events, Set Operations, DeMorgan's Laws, Kolmogorov Axioms, Inclusion-Exclusion, Birthday Problem | $P(A)$, $A^c$, $A \cup B$, $A \cap B$ |
| 3 | `Bolum3_Kosullu_Olasilik.ipynb` | Conditional Probability, Multiplication Rule, Law of Total Probability, Bayes' Theorem, Independent Events, Mutual Independence | $P(A \mid B)$, $P(A \cap B)$, Bayes |
| 4 | `Bolum4_Kesikli_Rasgele_Degiskenler.ipynb` | Random Variable Definition, CDF, PMF, Expected Value, Variance, Bernoulli, Binomial, Poisson, Geometric, Negative Binomial | $E[X]$, $\text{Var}(X)$, $\text{Bin}(n,p)$, $\text{Poi}(\lambda)$ |
| 5 | `Bolum5_Surekli_Rastgele_Degiskenler.ipynb` | PDF, CDF, Expected Value and Variance, Uniform Distribution, Normal Distribution, z-Transform, Binomial Approximation, Distribution of a Function | $f(x)$, $F(x)$, $\mathcal{N}(\mu, \sigma^2)$, $z$-score |
| 6 | `Bolum6_BirlikteDagilimliRD.ipynb` | Joint CDF, Discrete/Continuous Joint Distributions, Marginal and Conditional Distributions, Independent RVs, Convolution | $F_{X,Y}(x,y)$, $f_{X \mid Y}$, convolution |
| 7 | `Bolum7_Beklenen_Deger_Ozellikleri.ipynb` | Expectation of $g(X,Y)$, Linearity of Expectation, Product Expectation, Covariance, Correlation, Conditional Expectation, Conditional Variance, Moment Generating Functions | $E[XY]$, $\text{Cov}(X,Y)$, $\rho$, MGF |

---

## 🗂️ Repository Structure

```
olasilik-ve-istatistik/
│
├── README.md
├── requirements.txt
│
├── Bolum1_Kombinatoryal_Analiz.ipynb
├── Bolum2_Olasilik_Aksiyomlari.ipynb
├── Bolum3_Kosullu_Olasilik.ipynb
├── Bolum4_Kesikli_Rasgele_Degiskenler.ipynb
├── Bolum5_Surekli_Rastgele_Degiskenler.ipynb
├── Bolum6_BirlikteDagilimliRD.ipynb
└── Bolum7_Beklenen_Deger_Ozellikleri.ipynb
```

---

## ⚙️ Setup and Usage

### Requirements

- Python 3.10 or higher
- JupyterLab or Jupyter Notebook

### Environment Setup

```bash
# Clone the repository
git clone https://github.com/HAYDARKILIC/olasilik-ve-istatistik.git
cd olasilik-ve-istatistik

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

*Haydar Kilic, Artificial Intelligence Engineering