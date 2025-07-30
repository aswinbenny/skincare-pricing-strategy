# 💡 Skincare Product Pricing Strategy Analysis

This project explores data-driven pricing optimization for skincare products, based on real-world product data extracted from a PDF as part of a coding challenge.

The goal was to analyze the impact of strategic price adjustments on revenue, profit, and market positioning across 10 popular moisturizers in the K-beauty space.

---

## Interactive Tableau Story

Explore the project insights and simulations in this interactive Tableau Story:

[View the Skincare Pricing Strategy Story on Tableau Public](https://public.tableau.com/views/ProductMarginPricingVisualizerSkinSeoul/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

The story includes:
- Sales and profit analysis by price segment
- Revenue shifts from strategic price changes
- An interactive **Subscribe & Save simulator** to test how recurring discounts impact net profit

---

## Problem Statement

Given sales data, competitor pricing, and stock availability for skincare products, how can we adjust prices to:

- Improve overall profit margin
- Remain competitive in the market
- Optimize pricing by segment (Essentials, Mid-Tier, Premium)

---

## Dataset Overview

The dataset contains the following fields:

- `Product`, `Brand`, `Price (USD)`, `Cost Price (USD)`
- `Units Sold`, `Revenue (USD)`, `Stock Availability (Days)`
- `Competitor Price (USD)`

Additional columns like `New Price`, `Price Difference`, `Profit Margin`, and segment labels were created through data processing.

---

## Key Techniques Used

- **Pandas** for data transformation and margin calculations
- **Matplotlib & Seaborn** for business-focused visualizations
- **Segmentation** based on price tiers
- **Profit simulations** under adjusted pricing
- **Bar and pie charts** for financial storytelling

---

## Outputs

- All generated **figures and charts** are saved in the `figures/` folder.
- A comprehensive business-style **PDF report** summarizing insights and strategy is also included in the `pdf/` folder.

---

## How to Run

1. Clone the repository
2. Install requirements:

```bash
pip install -r requirements.txt