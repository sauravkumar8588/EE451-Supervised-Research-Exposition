
---

## Algorithms

**Adaptive LQR**
- Regularized Least Squares for parameter estimation
- Confidence ellipsoids for uncertainty quantification
- OFU (Optimism in the Face of Uncertainty) principle for control

**Thompson Sampling LQR**
- Bayesian sampling within confidence set for parameter updates
- Computes control policy via Riccati equation

---

## Usage

1. **Clone the repo:**
    ```
    git clone https://github.com/[your-username]/ee451-adaptive-lqr-thompson-sampling.git
    cd ee451-adaptive-lqr-thompson-sampling
    ```
2. **Install dependencies:**
    ```
    pip install -r requirements.txt
    ```
3. **Run simulations:**
    ```
    python src/adaptive_lqr.py
    python src/thompson_sampling.py
    ```
4. **View results:**
    - Output plots and data are saved in `/plots/`
    - Reports and detailed explanations in `/reports/`

---

## Authors

- Saurav Kumar (21D070063)
- EE451, IIT

## References

- Abbasi-Yadkori & Szepesvári, "Regret Bounds for Adaptive Control of Linear Quadratic Systems", 2011
- Abeille & Lazaric, "Thompson Sampling for Linear Quadratic Control Problems", 2017
- Sutton & Barto, "Reinforcement Learning: An Introduction", 2018

---

For questions, open an issue or contact the author.
