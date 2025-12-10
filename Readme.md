# Flipkart E-commerce Data Analysis  
 
### Comprehensive Data Cleaning, EDA & Business Insights using Python

This project performs an end-to-end exploratory data analysis (EDA) of a Flipkart product dataset.  
The goal is to understand product categories, pricing patterns, brand influence, and discount behavior through statistical exploration and data visualization.


##  Project Highlights

- Cleaned and structured raw categorical & textual data  
- Extracted main categories,sub-category and leaf-category from messy nested category strings  
- Created new features such as discount percentage  
- Analyzed pricing, discounting, category performance & brand patterns  
- Generated 10+ high-quality visualizations  
- Derived business-ready insights for decision-making  


##  Data Cleaning**

Key steps:

- Removed null and duplicate values and inconsistent rows  
- Parsed `product_category_tree` to extract main_category,sub-category and leaf-category.
- Normalized brand names and replaced missing brands with Unknown
- Cleaned nested dictionaries in product_specifications 
- Fixed price fields and calculated discount_percent 
- Removed or capped extreme outliers for visualization  


##  Exploratory Data Analysis (EDA)**

Visualizations created include:

- **Number of Products by Category**  
- **Top 10 brands by product count**
- **Average Retail Price by Category**  
- **Average Discount % by Category**  
- **Retail Price Distribution (Histogram)**   
- **Boxplot: Price by Top 10 Category**  
- **Boxplot: Price by Top 10 Brands**  
- **Correlation Heatmap**  

All images are available in the `/visuals` folder.


## Tech Stack**

Python
Pandas
Matplotlib
Seaborn
Jupyter Notebook
VS Code
Git & Github


## Key Business Insights**

- **Clothing** is the largest category, indicating a highly saturated and competitive segment.
- **Furniture and Automation** categories show the highest average retail prices, reflecting a premium product strategy.
- **Discount percentage is weakly correlated with retail price**, meaning sellers give discounts independently of price value.
- **Jewellery and Electronics contain extreme price outliers**, suggesting a wide mix of luxury and affordable items.
- **Brands show large variation in price ranges**, revealing clear differences between premium and budget brands.

---

## Folder Structure**

FLIPKART DATASET/
│
├── data/
    |flipkart.csv
│   |flipkart_cleaned.csv
│
├── visuals/
│   |*.png (all charts)
│
├── notebook/
│   |flipkart_eda.ipynb
│
├── README.md
└── requirements.txt

## How To Run**

pip install -r requirements.txt (Install dependencies)
jupyter notebook  (launch notebook)
Then open notebook/flipkart_eda.ipynb.  

## Conclusion**

This analysis provides a deep understanding of Flipkart's product ecosystem.  
We observe strong price variability, inconsistent discounting patterns, and a category structure dominated by low-to-mid price items.  
The insights derived here can help optimize:

- Pricing strategy  
- Inventory decisions  
- Marketing focus  
- Brand positioning  


