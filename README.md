# Amazon-Laptop-Market-Analysis

## 📌 Project Overview

This project focuses on analyzing laptop product data collected from Amazon India using Exploratory Data Analysis (EDA). The main objective is to understand laptop brands, pricing patterns, discounts, customer ratings, and specifications to identify useful trends and business insights.

## 🎯 Business Problem

The laptop market offers a wide variety of brands, models, specifications, prices, and discounts, making it difficult for customers to choose the right laptop. Businesses also need to understand customer preferences, competitor pricing, and popular laptop configurations. This project analyzes Amazon laptop data to identify meaningful patterns and support data-driven decisions.

## 🎯 Project Objectives

- Analyze 300 cleaned laptop records.
- Compare brands based on product count, average price, discount, and rating.
- Identify popular RAM and ROM capacities.
- Analyze price, discount, and rating distributions.
- Explore relationships between price, RAM, ROM, discount, and rating.
- Perform statistical analysis and hypothesis testing.
- Generate business insights and recommendations.

## 🛠️ Tools and Technologies

- **Python** – Programming and data analysis
- **Pandas** – Data cleaning and manipulation
- **NumPy** – Numerical operations
- **Requests** – Web requests for data collection
- **BeautifulSoup** – Web scraping
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Interactive analysis

## 📊 Dataset Description

The cleaned dataset contains **300 laptop records and 10 columns**.

| Column | Description |
|---|---|
| Brand | Laptop brand name |
| Model | Laptop model |
| RAM | RAM capacity in GB |
| ROM | Storage capacity in GB |
| Processor | Processor information |
| Intel Core | Intel Core information, where available |
| Windows | Operating system information |
| Price | Laptop price in Indian rupees |
| Discount | Discount percentage |
| Rating | Customer rating |

## 🔄 Project Workflow

1. **Data Collection:** Collected laptop product information from Amazon India.
2. **Data Cleaning:** Handled missing values, converted data types, and standardized price, discount, RAM, and ROM values.
3. **Data Preprocessing:** Prepared the dataset for analysis.
4. **Univariate Analysis:** Analyzed individual variables using charts and summary statistics.
5. **Bivariate Analysis:** Examined relationships between two variables.
6. **Multivariate Analysis:** Compared multiple variables to identify patterns.
7. **Statistical Analysis:** Applied hypothesis testing and correlation analysis.
8. **Insights and Recommendations:** Summarized findings to support business decisions.

## 📈 Exploratory Data Analysis

### 1. Univariate Analysis
- Laptop count by brand
- RAM and ROM distribution
- Price distribution
- Discount distribution
- Customer rating distribution
- Processor and Windows distribution

### 2. Bivariate Analysis
- Brand vs. Price
- Brand vs. Rating
- Brand vs. Discount
- Price vs. Discount
- Price vs. Rating
- RAM vs. Price
- ROM vs. Price

### 3. Multivariate Analysis
- Brand, Price, Rating, and Discount comparison
- RAM, Price, and Rating relationships
- Comparison of laptop specifications and pricing patterns

## 🔍 Key Insights

- **512 GB** was the most common storage capacity, appearing in 225 records.
- Average laptop prices differed significantly across brands.
- Average laptop prices differed significantly across RAM capacities.
- Price and discount showed a weak negative correlation in the analyzed dataset.
- Visualizations helped identify popular configurations and differences in pricing across brands.

## 🧪 Hypothesis Testing Results

### 1. Price vs. Brand
- **Test:** One-way ANOVA
- **F-statistic:** 5.54
- **P-value:** 4.06 × 10⁻¹²
- **Decision:** Reject the null hypothesis.
- **Insight:** Average laptop prices differ significantly across brands.

### 2. Price vs. RAM
- **Test:** One-way ANOVA
- **F-statistic:** 49.84
- **P-value:** 1.77 × 10⁻⁴⁷
- **Decision:** Reject the null hypothesis.
- **Insight:** Average laptop prices differ significantly across RAM capacities.

### 3. Discount vs. Price
- **Test:** Pearson Correlation
- **Correlation coefficient:** -0.256
- **P-value:** 3.16 × 10⁻⁶
- **Decision:** Reject the null hypothesis of no correlation.
- **Insight:** There is a statistically significant but weak negative relationship between discount and price.

*Note: These findings describe the collected dataset and do not necessarily represent the entire Amazon India laptop market. Correlation does not establish causation.*

## 💡 Business Recommendations

- Compare prices across brands before purchasing a laptop.
- Select RAM and storage according to usage requirements and budget.
- Consider customer ratings along with price and specifications.
- Compare discounts and actual prices before deciding on value for money.
- Businesses can use competitor pricing and popular specifications to improve product positioning and pricing strategies.

## ▶️ How to Run the Project

1. Download or clone the project repository.
2. Install the required Python libraries:

```bash
pip install pandas numpy requests beautifulsoup4 matplotlib seaborn jupyter
```

3. Open the project notebook using Jupyter Notebook or JupyterLab.
4. Ensure the dataset file is available at the path specified in the notebook.
5. Run the notebook cells in order to reproduce the analysis.

## 🏁 Conclusion

This project demonstrates the use of Python and Exploratory Data Analysis to transform raw laptop product data into meaningful insights. It covers data collection, cleaning, visualization, statistical testing, and business recommendations. The project strengthened practical skills in data analysis and data-driven decision-making.

## 👩‍💻 Author

**Data Analytics Learner**  
Completed as part of the Data Analytics learning journey at **Innomatics Research Labs**.
