# U.S. Alcohol Consumption Analysis & Beverage Trends (1977 - 2023)

An end-to-end data analytics project exploring the historical evolution of alcohol consumption in the United States, with a modern 10-year zoom-in (2013–2023) to validate market substitution effects.

## 📊 Key Insights & Findings
* **The Historical Crossover:** In 2022, Spirits officially overtook Beer as the most consumed beverage category per capita in the US.
* **The Substitution Effect:** Statistical testing (Pearson and Kendall correlations) confirms an inverse structural relationship—consumers are actively migrating from beer to spirits.
* **Simpson's Paradox Unmasked:** Pooled state-level data initially showed a false positive correlation (+0.22) due to geographic volume traits, but grouping by annual timelines revealed the true negative trend.
* **Business Takeaway:** While spirits are winning the market share, overall ethanol consumption per capita is slightly declining.

## 🛠️ Tech Stack & Methods
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Statistical Tests:** Pearson Correlation Coefficient, Kendall's Tau Monotonic Test

## 📂 Project Structure
* `data/`: Contains the raw time-series dataset.
* `notebooks/`: Jupyter Notebook with clean code, documentation, and plots.
* `reports/`: Exported HTML interactive report.

---
*Note: For a more business-friendly version with hidden code blocks and executive summaries, please visit my [Notion Case Study](TU_LINK_DE_NOTION_AQUI).*
