# ✈️ Airline Risk & Insurance Policy Analysis

This repository contains a project where we analyzed and recommended the most cost-effective **aircraft insurance policy** for a newly merged international airline. The analysis applied **quantitative modeling (Monte Carlo simulations)** and **financial risk assessment** to support strategic decision-making under uncertainty.

---

## 📌 Project Overview

The project scenario involved a recently merged airline with a highly leveraged financial structure and ambitious global expansion plans. To ensure financial stability, the airline needed to secure a **multi-year insurance policy** that balanced:

- **Cost efficiency** – minimizing premium and loss-related expenses.  
- **Risk coverage** – protecting the airline against catastrophic losses.  
- **Cash flow stability** – keeping maximum potential losses below a set threshold.  

Our objective was to evaluate multiple insurance options and recommend the one that best supports both financial and operational goals.

---

## 🔍 Methodology

1. **Fleet & Policy Setup**  
   Defined aircraft replacement values, insurance plan terms (premiums, deductibles, coverage limits).  

2. **Monte Carlo Simulation**  
   - Modeled crash events using industry-standard accident probabilities.  
   - Adjusted for a newer fleet assumed to be **25% safer** than the industry average.  
   - Conducted **100,000 simulation runs** to capture a distribution of possible outcomes.  

3. **Cost Analysis**  
   Calculated expected five-year costs for each plan, including premiums and covered losses.  

4. **Sensitivity Analysis**  
   Compared outcomes under baseline vs. safer fleet conditions.  

---

## 📂 Repository Contents

- `Analysis_Notebook.ipynb` – Python notebook with simulation and cost modeling.  
- `Executive_Summary.pdf` – Concise business-oriented summary.  
- `Presentation.pdf` – Visual presentation of methods, results, and recommendation.  

---

## 🛠️ Tools & Techniques

- **Python**: pandas, numpy, matplotlib for simulation & visualization  
- **Statistical Modeling**: Monte Carlo simulation with 100,000 iterations  
- **Scenario Testing**: Sensitivity analysis under different fleet safety assumptions  

---

