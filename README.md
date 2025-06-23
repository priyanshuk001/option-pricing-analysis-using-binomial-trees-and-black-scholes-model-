# 📈 Comparative Analysis of European Option Pricing

This project presents a **comparative analysis** of two widely-used techniques in option pricing: the **Binomial Tree model** and the **Black-Scholes analytical formula**. It focuses on pricing European call and put options, comparing the accuracy and convergence of both methods.

---

## 🧠 Objectives

- Implement the **Binomial Tree** model for European options
- Apply the **Black-Scholes** formula for analytical pricing
- Compare outputs of both models under varying parameters
- Analyze convergence behavior of the binomial model toward Black-Scholes pricing

---

## 📚 Theoretical Overview

- **Black-Scholes Model**: Provides a closed-form solution for European options, assuming log-normal asset price movement and no arbitrage.
- **Binomial Tree Model**: A step-wise discrete-time model that approximates the price movement and option value recursively.

---

## 📈 What’s Inside

- Functions to calculate call and put prices using:
  - Black-Scholes formula
  - Binomial Tree model
- Visual comparison of price vs. number of binomial steps
- Analysis of convergence and model accuracy
- Comparison across multiple strike prices, volatilities, and maturities

---

## 🧰 Libraries Used

- NumPy
- SciPy
- Matplotlib

---

## 🚀 How to Run

1. Clone this repository or download the notebook.
2. Install dependencies:
   ```bash
   pip install numpy scipy matplotlib
3. Open option_pricing_prediction.ipynb in Jupyter or VSCode.
4. Execute cells sequentially to view outputs and plots.
