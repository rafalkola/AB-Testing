# A/B Testing – E-commerce Recommendation System

## Project Overview

This project presents an A/B testing analysis of a product recommendation system implemented on an e-commerce platform. The goal is to evaluate whether the new recommendation algorithm improves user behavior and business outcomes compared to the existing system.

Three key performance indicators (KPIs) are used to measure the impact:

- **Purchase Rate** – the percentage of users who made a purchase after seeing a recommendation,
- **Return Rate** – the percentage of users who returned to the platform after their first session,
- **Average Time to Purchase** – the average time (in days) from the first interaction to purchase.

---

## Project Structure

A:B_Testing.ipynb # Main Jupyter Notebook with analysis and visualizations
Book1.twb # Tableau dashboard (optional visualization layer)
df_full.csv # Merged dataset with users, interactions, and product info
interactions.csv # User interaction logs with recommended products
products.csv # Product metadata
users.csv # User-level metadata including group assignment (test/control)

---

## Methodology

- Split users evenly into **test** and **control** groups.
- Collected ~600,000 interaction records.
- Performed data wrangling and exploratory analysis.
- Calculated KPIs for both groups.
- Conducted statistical hypothesis testing.
- Visualized results using Tableau.

---

## Key Findings (Synthetic Example)

- **Purchase Rate**: Test group 25% vs. Control group 20%
- **Return Rate**: Test group 44% vs. Control group 18%
- **Avg. Time to Purchase**: Test group converted faster on average (slighlty differences)

---

## Tech Stack

- Python (Pandas, NumPy, SciPy)
- Jupyter Notebook
- Tableau (for dashboarding)
- Git/GitHub (for version control)

---

> **Disclaimer**: All datasets used in this project are synthetically generated for portfolio and educational purposes. They do not represent real users or business data.

## Conclusion

The analysis demonstrates how A/B testing can be used to assess product changes in a data-driven way. In this synthetic case, the new recommendation engine led to improvements across all three KPIs.

---
