# Market Basket Analysis Using Python

## Project Overview
This project analyzes grocery purchase data to identify frequently purchased products and discover product combinations using Market Basket Analysis.

## Objectives
- Identify the most frequently purchased products.
- Find products commonly bought together.
- Calculate Support, Confidence, and Lift.
- Provide recommendations for retail product placement and cross-selling.

## Dataset
The dataset contains 38,765 grocery purchase records with these columns:
- `Member_number`
- `Date`
- `itemDescription`

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## Methodology
1. Load and clean the grocery dataset.
2. Analyze product purchase frequency.
3. Group purchases by customer and date into baskets.
4. Identify frequently co-purchased product pairs.
5. Calculate association-rule metrics.
6. Filter rules using a minimum pair count of 20 and Lift greater than 1.

## Results
- Whole milk was the most frequently purchased product in the initial analysis.
- Several product pairs involving milk, vegetables, and rolls/buns appeared frequently.
- Association rules were evaluated using Support, Confidence, and Lift.

## Business Applications
Retailers can use these patterns to explore product bundles, cross-selling, and store product placement.

## Limitations
The dataset has no explicit transaction ID. Grouping purchases by customer and date may combine separate shopping visits. Association does not prove causation.

## How to Run
1. Download the notebook `Market_Basket_Analysis.ipynb`.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the notebook and the grocery CSV dataset.
4. Run the notebook cells from top to bottom.

## Disclaimer
This is an educational project using a grocery dataset. Recommendations should be validated before real-world use.
