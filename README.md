# A/B Testing – E-commerce Recommendation System

## Project Overview

This project presents an A/B testing analysis of a product recommendation system implemented on an e-commerce platform. The goal is to evaluate whether the new recommendation algorithm improves user behavior and business outcomes compared to the existing system.

Three key performance indicators (KPIs) are used to measure the impact:

- **Purchase Rate** – the percentage of users who made a purchase after seeing a recommendation,
- **Return Rate** – the percentage of users who returned to the platform after their first session,
- **Average Time to Purchase** – the average time (in days) from the first interaction to purchase.

---

## Project Structure

    AB-TESTING/
    │
    ├── A:B_Testing.ipynb      # Main Jupyter Notebook with analysis and visualizations
    ├── Book1.twb              # Tableau dashboard (optional visualization layer)
    ├── df_full.csv            # Merged dataset with users, interactions, and product info
    ├── interactions.csv       # User interaction logs with recommended products
    ├── products.csv           # Product metadata
    └── users.csv              # User-level metadata including group assignment (test/control)

**Note: The CSV datasets used in this analysis are synthetic and not included in the repository.  
If you would like to reproduce the results, please contact me or refer to the code structure to simulate data.
---

## Methodology

- Split users evenly into **test** and **control** groups.
- Collected ~600,000 interaction records.
- Performed data wrangling and exploratory analysis.
- Calculated KPIs for both groups.
- Conducted statistical hypothesis testing.
- Visualized results using Tableau.

---

## Tableau Dashboard

You can explore the interactive dashboard here:  
🔗 https://public.tableau.com/app/profile/rafal.kolakowski/viz/Book1_17429045148440/Dashboard1?publish=yes

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

## Conclusion

The analysis demonstrates how A/B testing can be used to assess product changes in a data-driven way. In this synthetic case, the new recommendation engine led to improvements across all three KPIs.
