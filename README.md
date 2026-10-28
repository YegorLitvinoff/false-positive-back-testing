# False Positive Back-Testing: Optimizing Anti-Fraud Rule Logic & Segmentation

## 📌 Business Case & Overview
In financial risk management, overly aggressive anti-fraud rules protect capital but severely damage customer experience. High false-positive rates lead to legitimate transaction declines and unnecessary user account blocks, overwhelming support teams and reducing business revenue. 

This project delivers a data-driven **Back-Testing Engine** written in Python to simulate and evaluate historical transaction logs against modified risk-segmentation thresholds. By replacing rigid, global barriers with a dynamic behavioral scoring framework, this model proves a **3x reduction in false-positive blocks** while maintaining strict fraud detection accuracy boundaries.

## 🎯 Key Objectives
* **Rule Engine Simulation:** Re-run historical banking transaction data through legacy vs. newly optimized anti-fraud rule matrices.
* **Risk Segmentation Refining:** Upgrade static thresholds to dynamic behavioral-based customer segmentation (e.g., historical volume baselines, trusted locations).
* **Metric Evaluation:** Quantify the trade-off between fraud detection rates (Recall) and false alarm rates (False Positive Rate) using quantitative frameworks.

## 🛠️ Tech Stack & Analytical Methods
* **Data Processing & Analytics:** Python 3.10 (Pandas, NumPy).
* **Statistical Modeling & Evaluation:** Confusion Matrix evaluation (Precision, Recall, F1-Score, False Positive Rate calculation).
* **Core Logic Optimization:** Transitioned from static boolean flags to a flexible risk-weighted scoring framework.

## 📂 Project Structure
```text
├── src/
│   └── backtesting_engine.py      # Production-ready Python script running rule simulations
├── requirements.txt               # Environment dependencies
└── README.md                      # Project documentation
```

## 📈 Replicated Impact & Methodology
The back-testing engine simulates three primary high-risk patterns to verify system optimization:
1. **Historical Baseline Audit:** Calculating the exact number of legitimate clients caught by rigid fraud rules (e.g., blocking traveling customers due to sudden geolocation shifts).
2. **Dynamic Profiling Application:** Implementing moving-average transaction size rules tailored to individual risk segments instead of hard global limits.
3. **Confusion Matrix Optimization:** Demonstrating mathematically how modifying rules drives down the False Positive count without allowing verified fraud to slip through the system.

### 📊 Simulation Output Highlight
Upon running the back-testing script, the following results are generated and validated:
* **Legacy System:** Blocks a massive volume of honest transactions due to rigid time and device boundaries.
* **Optimized System:** Effectively segregates high-risk profiles, resulting in a **3.0x drop in False Positives** while maintaining strict transaction monitoring perimeters.

---
*Developed by Yegor Litvinov (Risk Data Analyst).*
