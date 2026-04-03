# Dating_Algorithms_Human_Bias

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Plotly](https://img.shields.io/badge/Visualization-Plotly-brightgreen.svg)

## 📌 Project Overview
What actually drives two strangers to want to see each other again after only 4 minutes? This project analyzes a dataset of **6,000+ speed dating events** (Columbia University) to identify the real triggers of human attraction, moving beyond what people *claim* they want to focus on what they actually *choose*.

### 🧪 Methodology & Data Cleaning
A high priority was placed on **data integrity**:
- **Wave Exclusion**: Waves 6 to 9 were removed due to inconsistent scoring scales (1-10 vs. 100-point allocation), preventing statistical bias.
- **Preprocessing**: Handled missing values and standardized attribute naming for cross-gender comparison.
- **Robustness**: The final dataset maintains over 6,000 observations, ensuring statistically significant conclusions.

---

## 📊 Key Insights

### 1. The Intelligence Paradox
While **Intelligence** is the highest-rated attribute on average (**7.33/10**), it shows a weak correlation with the final decision. In a high-pressure, short-duration environment, high IQ is often a "presumed" trait that doesn't necessarily trigger a "Yes."

### 2. The Primacy of Attractiveness (Halo Effect)
Physical attractiveness is the #1 predictor of success (**r = 0.48**). It acts as a binary filter: below a score of **7/10**, a participant's other qualities (ambition, sincerity) are statistically ignored by the partner.


### 3. The "Friction Zone"
**Shared Interests** consistently receive the lowest scores in the dataset. Unlike attractiveness or fun, which are immediate perceptions, sharing interests requires active mutual construction. This is the ultimate "dealbreaker" zone in a 4-minute window.

### 4. Gender Asymmetry
- **Women**: Are judged more strictly on physical appearance (a **-0.54 pts** gap compared to men).
- **Men**: Face a "status filter," being penalized more heavily on perceived **Ambition** (a **-0.35 pts** gap compared to women).

---

## 🛠️ Tech Stack
- **Analysis:** Pandas, Numpy
- **Visualization:** Plotly Express & Graph Objects (Custom Dark Theme)
- **Environment:** Jupyter Notebook

## 📈 Visualizations Included
The notebook features advanced interactive charts:
- **Radar Charts**: Comparing holistic gender profiles.
- **Heatmaps**: Visualizing scoring biases and "hot/cold" zones.
- **Correlation Bar Charts**: Ranking the actual weight of decision factors.

---

## 💡 Conclusion
The data suggests that speed dating is an **emotional reaction**, not a rational audit. To maximize matches, efforts should focus on **Fun** and navigating the **Friction Zone** of shared interests, rather than over-demonstrating intellectual traits which are already largely assumed.
