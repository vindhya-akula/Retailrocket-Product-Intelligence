# Retailrocket Product Intelligence & Recommendation Analytics

An interactive five-page Power BI dashboard that explores e-commerce product behavior and evaluates product recommendation models using the Retailrocket dataset.

## Project Overview

This project combines Python-based data profiling, product analytics, and recommendation model evaluation to understand user interactions and assess how effectively recommendation approaches predict the next product a user will view.

The dashboard is organized into five pages:

1. **Executive Overview** — High-level e-commerce activity and key performance indicators.
2. **Product Analytics** — Product engagement, views, cart activity, and transaction patterns.
3. **Recommendation Analytics** — Comparison of five recommendation approaches.
4. **Model Reliability** — Evaluation of recommendation performance across different historical transition-support groups.
5. **Model Insights** — Key findings, model performance, and cold-start analysis.

## Dashboard Preview

### 1. Executive Overview

![Executive Overview](Screenshot%202026-10-28%20152552.png)

### 2. Product Analytics

![Product Analytics](Screenshot%202026-10-28%20152614.png)

### 3. Recommendation Analytics

![Recommendation Analytics](Screenshot%202026-10-28%20152639.png)

### 4. Model Reliability

![Model Reliability](Screenshot%202026-10-28%20152703.png)

### 5. Model Insights

![Model Insights](Screenshot%202026-10-28%20152724.png)

## Key Results

- **2.75M+** e-commerce interaction events analyzed.
- **5** recommendation approaches compared using offline evaluation.
- **14.97% Recall@10** achieved by the hybrid recommendation model.
- **9.60% NDCG@10** achieved by the hybrid recommendation model.
- **15.98%** of test examples represented cold-start cases.
- **22.21% Recall@10** for cases with more than 10 historical transitions.
- **1.55% Recall@10** for cases with no learned transition recommendations.

### Evaluation Note

The recommendation models were evaluated on a chronological test split for next-product-view prediction. These metrics measure recommendation ranking performance and do not represent actual purchase conversion, revenue growth, or business impact.

## Tools & Technologies

- **Power BI** — Interactive dashboards and data visualization
- **DAX** — KPI measures and analytical calculations
- **Power Query** — Data transformation
- **Python** — Data profiling and analysis
- **Pandas** — Data cleaning and manipulation
- **Jupyter Notebook** — Exploratory data analysis

## Dataset

The project uses the publicly available Retailrocket e-commerce dataset.

**Source:** [Retailrocket E-commerce Dataset — Kaggle](https://www.kaggle.com/retailrocket/ecommerce-dataset)

The dataset contains user interaction events and product-related information. Raw dataset files are not included in this repository.

## Repository Contents

- `01_data_profiling.ipynb` — Data profiling and exploratory analysis
- `hybrid_branch_performance.csv` — Hybrid recommendation branch performance
- `model_comparison_results.csv` — Recommendation model comparison results
- `product_analytics_metrics.csv` — Product-level analytical metrics
- `product_session_funnel.csv` — Session funnel metrics
- `product_transition_support.csv` — Historical transition-support analysis
- `support_level_recall.csv` — Recommendation recall by support level
- Dashboard screenshots — Visual previews of all five report pages

## Key Learnings

- Profiling and analyzing large-scale e-commerce interaction data
- Building interactive Power BI dashboards
- Developing and validating DAX measures
- Comparing recommendation models using Recall@10 and NDCG@10
- Investigating cold-start behavior and historical support
- Communicating analytical findings through visualizations

## Project Links

- **GitHub Repository:** [Retailrocket Product Intelligence](https://github.com/vindhya-akula/Retailrocket-Product-Intelligence)
- **Dataset:** [Retailrocket on Kaggle](https://www.kaggle.com/retailrocket/ecommerce-dataset)
- **LinkedIn Project Post:** Add your LinkedIn post URL here once published.
- **Power BI Report:** Interactive report or downloadable `.pbix` link can be added here when available.

## Author

**Vindhya Akula**

Data Analytics | Business Intelligence | Python | Power BI | SQL

---

*This project was developed for analytical learning and portfolio demonstration.*
