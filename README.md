# Online Pet Supply – Sales, Profitability & Shipping Optimization Analysis

## 1. Project Objectives

The goal of this project was to analyze the sales performance, profitability, customer purchase behavior, and shipping costs of an online pet supply retailer. Specifically, the objectives are:

- **Sales & Profitability**: Identify top-performing categories, products, and regions driving sales and profit.

- **Cross-Sell Opportunities**: Detect product combinations and bundling opportunities to improve average order value.

- **Shipping Optimization**: Model the impact of tiered shipping discounts on overall shipping costs to uncover cost-saving opportunities.

## 2. Data & Tools

- **Dataset**: Online Pet Supply transactional sales dataset (includes product details, sales, profit, quantity, shipping cost, and region).

- **Tools Used**:
  - Power BI (data cleaning, modeling, and visualization)
  - DAX (custom measures, profit %, what-if scenario modeling)

- **Key Metrics**: Total Sales, Profit %, Customer LTV, Shipping Cost (baseline vs optimized).

## 3. Analysis Process

- **Data Preparation**

  - Cleaned and transformed raw sales data using Power Query.

  - Removed invalid/negative quantities (representing returned orders).

  - Created DAX measures for Profit %, Customer LTV, and What-if Shipping Scenarios.

- **Dashboard 1: Sales & Profitability Overview**

  - KPI Cards: Total Sales, Total Profit, Profit %, Shipping Cost, and Average Customer Lifetime Value(LTV).

  - Category & Product Analysis: Ranked sales by category and product.

  - Regional Analysis: Sales mapped by region/state to highlight geographic concentration.

  - Profitability Tree Map: Profit % contribution by product line.

  **Insight**: Electronics (44%) and Grooming (35%) are the largest profit drivers, while Food and Disposables dominate total sales. Pet Food, although smaller, is strategically important for repeat purchases.

- **Dashboard 2: Market Basket & Cross-Sell Opportunities**

  - Product Selector: Interactive slicer to filter product-specific combinations.

  - Combination Analysis: Identified which items are frequently purchased together.

  - Category-Level Profitability: Sales vs profit % by category.

  **Insight**: Food ($0.54M) and Disposables ($0.43M) lead in sales, but Grooming and Electronics deliver higher margins. Cross-sell opportunities exist in hygiene-related products (Dog & Puppy Pads + Poop Bags) and grooming products (Pet Grooming Brush, Pet Hair Remover).

- **Dashboard 3: Shipping Metrics & Cost Optimization**

  - KPI Cards: Baseline shipping, Optimized shipping (what-if), and Potential savings.

  - What-If Scenario: Tiered discount rates modeled by shipment size.

  - Product-Level Impact: Shipping cost by product before vs after optimization.

  - Category-Level Analysis: Average items per order to assess shipping leverage.

  **Insight**: Tiered shipping discounts can reduce costs by $118K (31%), lowering baseline shipping from $385K to $267K. Pet Food (5.3 items/order) and Cleaning Supplies (4.6 items/order) are the most impactful categories for cost optimization.

## 4. Final Results & Recommendations

- **Sales Growth Drivers**: Electronics and Grooming drive profitability, while Food and Disposables dominate sales volume.

- **Cross-Sell Potential**: Bundling hygiene and grooming products with Food/Disposables can increase order size and profit margins.

- **Shipping Optimization**: Implementing tiered discounts by shipment size yields 31% savings, especially for high-volume categories like Pet Food.

- **Strategic Recommendation**:

  - Focus promotions on cross-sell bundles (Food + Grooming/Disposables).

  - Encourage larger order sizes to maximize shipping discounts.

  - Monitor dependency on a few top-selling products to diversify revenue.
