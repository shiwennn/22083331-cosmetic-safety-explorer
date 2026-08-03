# 22083331-cosmetic-safety-explorer
System files for the Health Risk Analysis and Visualization of Cosmetic Product Ingredients Using Data-Driven Approaches project.

## Repository Contents

- `notebooks/` – Python notebooks for data exploration, preprocessing, quality checking, ingredient classification, product risk scoring, concern tagging and dashboard preparation
- `data/raw/` – Original product information dataset
- `data/processed/` – Cleaned and processed product data
- `data/quality_check/` – Ingredient quality-check outputs, canonical mappings and classification files
- `data/risk_scoring/` – Product risk scores, ingredient-level results and concern-tagging outputs
- `data/dashboard_views/` – Prepared datasets used to develop the Tableau dashboard
- `data/pre-post_survey/` – Aggregated pre-survey and post-survey results based on 200 participants
- `tableau/` – Tableau packaged workbook

## Project Links

- Project Landing Page: https://cosmetic-awareness.vercel.app
- Tableau Public Dashboard: https://public.tableau.com/views/COSMETICINGREDIENTDASHBOARD/D1_Overview?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Data Availability

The original data was obtained from the [Sephora Products and Skincare Reviews dataset on Kaggle](https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews).

The `product_info.csv` file is included in this repository. The five raw review CSV files and the processed review dataset are not included because of their large file sizes.

To run the review-related sections of Notebooks 01 and 02, download and extract the Kaggle dataset. Then place the following files in the local `data/raw/` folder:

- `reviews_0-250.csv`
- `reviews_250-500.csv`
- `reviews_500-750.csv`
- `reviews_750-1250.csv`
- `reviews_1250-end.csv`

The review files were used for initial data exploration but were not required for the final ingredient-risk analysis.

## Data Privacy

Only aggregated survey results are included. Individual participant responses and personal information are not shared.

## Disclaimer

The system provides ingredient-based screening information for educational purposes. It should not be treated as a complete toxicological or medical assessment.
