# 🚐 Swirltubs: Stochastic Optimization & Resource Allocation

## 🎯 Executive Summary
This project tackles a complex resource allocation and logistics challenge for Swirltubs, a company managing a network of 1,000 service technicians. The objective was to architect an optimal balance between holding costs and service delivery. Using predictive modeling and probability distributions, this project provides a data-driven strategy to maximize "fix-it-first" service rates while strictly controlling spatial and financial constraints.

## 🛠️ Methodology & Technical Execution
* **Stochastic Optimization:** Applied the binomial distribution and **Monte Carlo simulations** to model real-world uncertainty in demand and usage frequency.
* **Scenario Testing:** Executed 50 randomized stocking trials via automated macros to test the heuristic recommendation against unpredictable conditions, calculating revisit costs vs. net benefit per cubic foot.
* **Resource Categorization:** Implemented an **ABC Analysis** framework to prioritize inventory, ensuring the highest ROI for limited storage capacity (500 cubic feet constraint).

## 📊 Key Findings
* **Risk Mitigation:** The heuristic model successfully absorbed historical demand shocks, producing a final recommendation with a minimum 55% accuracy baseline under extreme random conditions.
* **Strategic Categorization:** Identified that Category A components (highest frequency) accounted for 52.64% of optimal inventory, providing a clear hierarchy for resource allocation.
* **Actionable Thresholds:** Established a data-proven baseline to automatically stock any resource demonstrating an 80% frequency occurrence across simulation trials, covering 291 high-value assets.

## 💡 Translation to Marketing & Business Strategy
While applied to supply chain, the underlying mechanics of this project demonstrate advanced capabilities in **Budget & Resource Optimization**. The ability to use Monte Carlo simulations to predict demand, categorize assets by ROI (ABC Analysis), and mitigate risk under uncertainty translates directly to optimizing media planning budgets, forecasting marketing campaign performance, and allocating ad spend across dynamic channels.
