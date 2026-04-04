# Andrew Sutcliffe  
**MSc Financial Engineering**

Montreal, Quebec & Amsterdam, the Netherlands
[LinkedIn](https://www.linkedin.com/in/andrew-j-sutcliffe/)

---

## Projects:

### American Option Pricing via Neural Operators
Implements a neural operator framework for learning the option pricing map directly: treating pricing as an operator learning problem rather than solving a PDE for each set of parameters. 

Includes:
- Training data generation of 10000 early-exercise boundaries using predictor-corrector numerical method
- FNO and MNO Model training 
- Evaluation of pricing accuracy across a range of parameters
- Speed comparison (showing speed ups of 27x & 43x vs pred-corr)
- Training Log showing other architecture tweaks and model iterations

This was done (in line with the paper) under the BS model. I'll be extending this to Heston soon where the early exercise boundary becomes a 2D surface, thus requiring 2D Neural Operators!

Repo: [Neural Operator American Option Pricing](https://github.com/AndrewJSut/neural-operator-option-pricing)

---

### Fourier-Cosine (COS) Method for European Option Pricing
Implements the COS method, a Fourier-based technique for pricing European options by approximating the risk-neutral density via cosine series expansions of the characteristic function. 

Includes:
- Modular cos_pricer library, takes as input: model char. function (BS, Heston) & payoff-specific fourier coefficients g_n
- Jupyter notebooks demonstrating convergence and accuracy for both BS and Heston
- Accuracy tunable to within any tolerance

Repo: [Fourier Option Pricing](https://github.com/AndrewJSut/fourier-option-pricing)

---

### McGill-FIAM Asset Management Hackathon 2025
A quantitative research pipeline that develops an institutional-grade multi-asset allocation system.  
We used a **Fourier Neural Operator (FNO)** to extract latent systemic risk factors from cross-sectional fundamentals, built **regime-conditioned MLP factor-premia models**, and optimized portfolio allocation using a **hierarchical reinforcement-learning structure**.

**Highlights:**  
- Extracted latent systemic risk factors using **Fourier Neural Operators (FNOs)**  
- Modelled market regimes using:  
  - **FinBERT sentiment scores** from corporate disclosures  
  - **Macro stress index**  
- Derived regime-conditioned factor premia via MLPs  
- Designed a **hierarchical RL allocator** (sector, country, global)  
- Maximized information ratio under institutional constraints:  
  - Turnover limits  
  - Tracking error constraints  
  - Position-size bounds  
- Built full backtesting pipeline + performance attribution 

---

### Dynamic Portfolio Allocation in Goals-Based Wealth Management  
Replicates and extends the model of Das, Ostrov, Radhakrishnan & Srivastav (2019).  

Includes:
- Efficient-frontier portfolio construction  
- Log-wealth grid discretization  
- Markov transition probabilities derived from GBM dynamics  
- Backward induction dynamic programming  
- In-sample and out-of-sample success probabilities  
- Wealth-distribution and policy-map visualizations

All code is modular for experimentation with grid size, range, and algorithmic variants.

**Repo:** [Dynamic Allocation GBWM](https://github.com/AndrewJSut/DynamicAllocationGBWM)

---

### Pricing Bermudan Options Using a Simplified Quadrature  
Implemented a numerical Bermudan option pricer using a simplified quadrature to efficiently approximate continuation values across early-exercise decision surfaces.

 **Repo:** [Option Pricing with Quadrature](https://github.com/AndrewJSut/QuadratureOptionPricing)

---

## Skills  
Python • R • C++
Risk modelling • Derivatives • Time-series Econometrics  
Machine Learning (sklearn, torch) 

---

<!--
-->
