# Interbank Crisis Detection Using Network Modeling

## 🚀 Objective

- Model interbank transactions as a temporal network.
- Extract and analyze network motifs (e.g., reciprocity, cyclic triads).
- Identify behavioral changes in the system before crises occur.
- Lay the foundation for a data-driven early warning system using statistical and machine learning methods.

---

## 🧠 Methodology

- **Dynamic Network Construction**: Each time window (e.g., day, week) forms a directed graph of transactions.
- **Feature Engineering**:
  - Reciprocity ratio
  - Cyclic closure
  - Degree distributions
- **Statistical Analysis**:
  - Hypothesis testing across stress vs. non-stress periods
  - Time-series comparison of motif prevalence
- **Clustering**: Unsupervised methods to group banks by behavior (e.g., transaction volume, counterparty diversity)
- **Modeling**: Linear and non-linear regression to link motif patterns with crisis onset.
