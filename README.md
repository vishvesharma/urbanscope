<div align="center">

<h1 style="margin-bottom:5px;">🌐 URBANSCOPE</h1>
<p style="margin-top:0; font-size:16px;">
AI-Powered Urban Intelligence Platform
</p>

<br>

<img src="https://img.shields.io/badge/Domain-Urban%20Analytics-6C63FF?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Focus-Risk%20%7C%20Safety%20%7C%20Sustainability-00C2FF?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Status-Active-22C55E?style=for-the-badge"/>

<br><br>

<p style="max-width:600px;">
A clean, insight-driven analytics system designed to understand how urban systems behave across environment, safety, infrastructure, and economy.
</p>

</div>

---

## 🧭 Overview

UrbanScope takes India's urban data seriously. We fuse six different datasets — air quality, crime patterns, road accidents, economic indicators, population density, and rainfall — to create a comprehensive view of how cities actually function.

The result? A data-driven understanding of urban risk, safety, and development that goes beyond surface-level statistics.

---

## 📊 What We Analyze

| Domain | Description |
|-------|------------|
| **Air Quality** | Pollution levels across pollutants (PM2.5, NO₂, SO₂, etc.) |
| **Safety** | Crime rates, chargesheeting efficiency, and accident patterns |
| **Infrastructure** | Postal density as a proxy for development accessibility |
| **Economy** | GDP trends and sector-wise growth indicators |
| **Environment** | Rainfall patterns and their correlation with urban factors |

---

## 🔍 Key Insights

We don't just collect data — we find the connections that matter:

* **Pollution Risk Score (PRS)**: Weighted composite of air quality metrics
* **Safety Index (SI)**: Crime rates balanced against law enforcement effectiveness
* **Development Index (DI)**: Infrastructure accessibility and economic indicators
* **Urban Risk Index (URI)**: Overall risk assessment combining all factors

> States with high pollution often show correlated safety challenges, but economic development doesn't always follow the expected patterns.

---

## 🛠️ Technical Approach

* **Data Fusion**: Cleaned and standardized 6 heterogeneous datasets
* **Feature Engineering**: Created domain-specific indices with statistical weighting
* **Machine Learning**: Random Forest and Gradient Boosting for risk prediction
* **Clustering**: PCA-based state grouping to identify urban archetypes
* **Visualization**: Dark-themed, publication-ready analytics dashboards

---

## 📈 Sample Results

**High-Risk States** (URI > 0.5):
- Delhi, Uttar Pradesh, Bihar show concerning patterns
- Pollution and safety issues compound each other

**Safe & Developed** (High SI + DI):
- Kerala, Tamil Nadu demonstrate balanced urban management
- Good infrastructure correlates with lower accident rates

**Unexpected Findings**:
- Some economically strong states still struggle with air quality
- Rainfall patterns show weak correlation with safety metrics

---

## 🚀 Quick Start

```bash
# Clone and navigate
git clone <repository-url>
cd urbanscope

# Install dependencies
pip install -r requirements.txt

# Run the analysis
jupyter notebook "1.ipynb"
```

> Datasets should be placed in the `datasets/` folder. The notebook handles cleaning and fusion automatically.

---

## 📋 Data Sources

* **AQI**: Central Pollution Control Board
* **Crime**: National Crime Records Bureau
* **Accidents**: Ministry of Road Transport & Highways
* **GDP**: Ministry of Statistics & Programme Implementation
* **Population**: Department of Posts (postal infrastructure data)
* **Rainfall**: India Meteorological Department

> ⚠️ Datasets vary in granularity (state, district, national). Handled carefully to avoid misleading conclusions.

---

## 🎯 Methodology Notes

* **Composite Scores**: Weighted averages using domain expertise
* **Normalization**: Min-max scaling for fair comparisons
* **Missing Data**: Median imputation for robustness
* **Validation**: 5-fold cross-validation on ML models

---

## 🤝 Contributing

This is an analytical framework that can be extended:

* Add more urban indicators (healthcare, education, transportation)
* Include temporal analysis for trend detection
* Expand to city-level granularity when data becomes available

---

## 📄 License

Open source — use it, improve it, share your findings.

---

*Built with Python, scikit-learn, matplotlib, and a focus on actionable urban insights.*</content>
<parameter name="filePath">/Users/vvsiscold/Downloads/URBAN SCOPE/README.md