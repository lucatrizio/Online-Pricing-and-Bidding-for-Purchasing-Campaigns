# Handling a Marketing Campaign: Pricing and Bidding  
*Online Learning Applications Project*  

**Politecnico di Milano – Applied AI in Biomedicine**  
**Authors:** Margherita Brogi, Alfonso Shytani, Luca Trizio  
**Date:** September 9, 2024  

---

## 📌 Project Description  
This project focuses on the application of **online learning algorithms** to optimize **pricing and bidding strategies** in digital marketing campaigns.  

We study both **stochastic** and **adversarial environments**, designing and comparing several algorithms for pricing and auction bidding. The project evaluates performance through **cumulative regret** and **utility-based metrics**, providing insights into how learning agents adapt under different conditions.  

---

## 📂 Project Structure  
The project is organized according to the following requirements:  

1. **Stochastic Environment**  
   - Pricing with Gaussian Processes  
   - Bidding with a UCB-like Algorithm  
   - Bidding with a Primal-Dual Algorithm  
   - Joint Pricing and Bidding (UCB-like / Primal-Dual)  

2. **Adversarial Environment**  
   - Discrete Pricing with EXP3  
   - Bidding with a Primal-Dual Algorithm (Non-truthful auctions)  
   - Pricing & Bidding Interaction  

3. **Extensions for Pricing**  
   - Sliding-Window UCB for non-stationary demand  
   - CUSUM-UCB for abrupt demand shifts  

4. **Comparison of Bidding Algorithms**  
   - UCB-like vs. Primal-Dual (truthful & non-truthful auctions)  
   - Multi-agent competition scenarios  

---

## ⚙️ Methodology  
- **Demand modeling:** decreasing linear functions (stochastic) and changing demand functions (adversarial).  
- **Auction design:** second-price (truthful) and generalized first-price (non-truthful).  
- **Evaluation metric:** cumulative regret vs. clairvoyant baseline.  
- **Exploration techniques:** UCB variants, Gaussian Processes, EXP3, and Primal-Dual optimization.  

---

## 📊 Results  
- **Stochastic setting:**  
  - Gaussian Process pricing achieved stable convergence with low regret.  
  - Primal-Dual bidding showed strong budget optimization.  

- **Adversarial setting:**  
  - EXP3 successfully adapted to dynamic pricing but with higher variance.  
  - Primal-Dual bidding ensured competitive strategies even in non-truthful auctions.  

- **Extensions:**  
  - Sliding-Window UCB improved adaptability to shifting demand.  
  - CUSUM-based methods performed better under abrupt regime changes.  

- **Comparison of agents:**  
  - Primal-Dual algorithms provided balanced performance.  
  - UCB-like strategies were competitive in stable environments but struggled under adversarial conditions.  
  - Adding a randomized agent helped highlight robustness differences.  

---

## 🧑‍💻 Authors  
- **Margherita Brogi**  
- **Alfonso Shytani**  
- **Luca Trizio**  
