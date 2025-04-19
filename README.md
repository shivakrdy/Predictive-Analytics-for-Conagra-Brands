# Predictive Analytics for Conagra Brands – Meat Substitutes

[![Python](https://img.shields.io/badge/Python-Data--Science-blue?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data--Wrangling-yellow?logo=pandas)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![UT Dallas](https://img.shields.io/badge/UTD-Project-green?logo=academia)](https://www.utdallas.edu/)

This project was conducted as part of a **collaborative academic-industry partnership between The University of Texas at Dallas and Conagra Brands**. The objective was to leverage **real-world retail and panel data provided by Conagra** to uncover data-driven strategies for future growth in the **Meat Substitutes category**, especially for their brand **Gardein**.

---

## 🏢 About Conagra Brands

**Conagra Brands** is a major consumer packaged goods company with over 100 household-name brands like:
- Birds Eye®
- Healthy Choice®
- Marie Callender’s®
- Gardein™ (focus of this project)
- Slim Jim®, and more

Conagra’s goal for this engagement was to understand shopper behavior, identify performance gaps, and optimize assortment, pricing, and merchandising strategies for its Meat Substitutes portfolio.

---

## Project Objective

The purpose of this project was to:
- Analyze sales and performance trends across Conagra’s Meat Substitute SKUs
- Uncover regional and demographic opportunity areas
- Model the impact of pricing, form, and merchandising on unit velocity
- Recommend an optimized product assortment and pricing strategy
- Present final insights to Conagra's leadership panel

---

## Data Sources

Conagra provided access to large-scale commercial data sets (20GB+) through their vendor **Circana**, including:

- **POS (Point of Sale) Data**  
  Weekly store- and item-level sales including dollar sales, unit sales, volume sales, and ACV/TPD metrics.

- **Panel Data**  
  Demographics, buyer penetration, repeat rate, buyer trip frequency, household spend, etc.

- **National Eating Trends (NET)**  
  Information on how, when, why, and what consumers eat; used to map motivations to product performance.

- **Metadata**  
  Product-level information such as: UPC, Aisle, Brand, Franchise, Flavor, Form, Meat Source, Package Size, and Count.

---

## 📁 Repository Structure

```
Predictive-Analytics-Conagra-Meat-Substitutes/
│
├── Phase 1_Exploratory Analysis/
│   ├── 01_Brand-Level_Sales_Trends.ipynb
│   ├── 02_Gardein_Brand_Analysis.ipynb
│   └── Conagra_Project_Report_Phase1.pdf
│
├── Phase 2_Pricing Merchandising Insights/
│   └── Conagra_Project_Report_Phase2.pdf
│
├── Phase 3_Product Mix Optimization/
│   ├── 03_Final_Conagra_Product_Analysis.ipynb
│   ├── Conagra_Project_Report_Phase3.pdf
│   └── Conagra_Summary_Presentation_Phase3.pptx
│
└── README.md
```

---

## Project Phases and Deliverables

### Phase 1: Exploratory Brand Analysis
- Built Python dashboards to explore trends by brand, region, aisle, form, and flavor.
- Used Seaborn/Matplotlib to visualize CAGR, YoY decline, and volume shifts.
- Identified underperforming SKUs by region and opportunity whitespace.
- Delivered written PDF summary covering brand positioning and historical growth.

### Phase 2: Pricing & Merchandising Analysis
- Analyzed price per unit, base vs. incremental sales, merchandising lift.
- Modeled unit velocity vs. pricing thresholds across multiple forms and flavors.
- Segmented products by price sensitivity and promotional responsiveness.
- Provided strategy recommendations: price tiers, merchandising triggers, competitive gaps.

### Phase 3: Product Optimization & Predictive Modeling
- Clustered SKUs by attribute: size, form, flavor, aisle, brand, pack count.
- Built predictive models (regression + decision trees) to forecast unit sales.
- Modeled “What-if” scenarios for new product launches and SKU rationalization.
- Delivered PowerPoint summary + Jupyter notebooks for reproducibility.

---

## Tools & Technologies Used

- **Python 3.8+**, Jupyter Notebook
- **pandas, numpy, seaborn, matplotlib**
- **Excel + PowerPoint, PowerBI + Tableau** for reporting and dashboards
- **Circana's commercial retail datasets**
- **Retail & CPG domain knowledge** (Meat Substitutes category)

---

## 👨‍💻 My Role

> I independently completed this project from end to end, including:
> - Cleaning and preprocessing 20GB+ of commercial sales and panel data  
> - Designing and executing exploratory and predictive models  
> - Developing stakeholder-ready business reports and visuals  
> - Delivering a final presentation to Conagra’s leadership panel

This was part of my graduate coursework in **Predictive Analytics** at **The University of Texas at Dallas**.

---

## Business Impact

The deliverables helped Conagra:
- Identify underperforming SKUs and regions
- Realign pricing and promotion strategies
- Focus product development toward high-growth forms and flavors
- Support data-driven decisions using predictive modeling

---

## Data Privacy & Availability

Due to privacy policies, proprietary data from Conagra and Circana is **not included** in this repository.

- The datasets are over 20GB in size and are commercially licensed.
- Only cleaned summaries, notebooks, and reports are included.

---

## 🤝 Industry Collaboration & Presentation

This project was conducted as part of a collaborative initiative between **UT Dallas** and **Conagra Brands**.

At the end of the project, I presented my findings and recommendations directly to the **Conagra management panel**, highlighting growth opportunities, pricing strategies, and assortment optimization grounded in predictive analytics.

This engagement helped bridge academic learning with real-world decision-making in a high-impact retail analytics setting.

---

