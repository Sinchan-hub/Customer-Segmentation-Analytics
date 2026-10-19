# Customer Segmentation Analytics

### Customer Segmentation Using Python, Machine Learning & Power BI

## 📌 Project Overview

Customer Segmentation Analytics is a data analysis and machine learning project that groups customers into distinct segments based on their characteristics and purchasing behavior. The project uses **Python, K-Means clustering, and Power BI** to analyze customer data and present meaningful patterns through an interactive dashboard.

The objective is to help businesses better understand their customers, identify differences in purchasing behavior, and support data-driven marketing and customer relationship management decisions.

## 🎯 Project Objectives

- Analyze customer demographics, income, and purchasing behavior.
- Perform exploratory data analysis (EDA) to identify patterns and trends.
- Prepare and preprocess customer data for machine learning.
- Apply K-Means clustering to group similar customers.
- Compare customer segments based on income, spending, and purchase recency.
- Develop an interactive Power BI dashboard for customer segment analysis.
- Support targeted marketing strategies through customer insights.

## 🛠️ Tools and Technologies

| Tool / Technology | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib / Seaborn | Data visualization, if used in the notebook |
| Scikit-learn | K-Means clustering and machine learning |
| Jupyter Notebook | Exploratory analysis and model development |
| Power BI | Interactive dashboard and reporting |
| DAX | Measures and calculated metrics in Power BI |

## 📂 Dataset Description

The project uses customer marketing campaign data containing demographic information, household details, purchasing behavior, and campaign responses.

The dataset includes fields related to:

- **Customer demographics:** Income, birth year, education, and marital status.
- **Household information:** Number of children and teenagers in the household.
- **Product spending:** Spending on wines, meat products, fish, fruits, sweets, and gold products.
- **Purchase channels:** Purchases through websites, catalogues, physical stores, and deals.
- **Customer activity:** Recency of the last purchase and website visit frequency.
- **Campaign engagement:** Acceptance of marketing campaigns and customer responses.

The data is prepared for analysis, with engineered features used to summarize customer spending, purchasing activity, household composition, and campaign acceptance.

*Note: Include the original dataset in the repository only if its licensing and redistribution terms permit public sharing.*

## ⚙️ Project Workflow

### 1. Data Loading

Loaded the customer dataset into Python using Pandas for inspection and analysis.

### 2. Data Cleaning and Preprocessing

- Inspected the dataset structure and data types.
- Identified missing values and examined data quality.
- Prepared relevant numerical and categorical features for analysis.
- Created additional features to summarize customer behavior.

### 3. Exploratory Data Analysis (EDA)

Explored customer demographics, income levels, product spending, purchase channels, and campaign engagement to understand the dataset and identify patterns.

### 4. Feature Engineering

Created aggregated features to provide a broader view of customer behavior:

- `Total_Spend` — combined spending across selected product categories.
- `Total_Purchases` — aggregated purchase activity across selected channels.
- `Total_Children` — combined children and teenagers in the household.
- `Total_Campaign_Accepted` — total accepted campaigns across the selected campaign fields.

### 5. Customer Segmentation Using K-Means

Applied the K-Means clustering algorithm to group customers into **five clusters**.

K-Means is an unsupervised machine learning algorithm that groups data points based on similarity in the selected feature space.

The resulting cluster labels are used to compare customer groups by income, spending, and purchasing behavior.

### 6. Power BI Dashboard Development

Built an interactive Power BI report to communicate the analysis through visualizations, KPIs, and cluster comparisons.

## 📊 Power BI Dashboard Features

The report contains two pages.

### Page 1: Customer Segmentation Overview

Provides a high-level summary of customer segmentation and purchasing behavior.

Key components:

- Total Customers KPI
- Total Segments KPI
- Average Spending KPI
- Customer distribution by cluster
- Product spending analysis
- Purchase channel analysis
- Customer cluster profiles

### Page 2: Customer Segment Analysis

Provides a more detailed comparison of the five customer clusters.

Key components:

- Customer distribution by cluster
- Average income by cluster
- Average spending by cluster
- Average recency by cluster
- Customer profile comparison table
- Cluster selection slicer for interactive filtering

The dashboard uses a dark-themed design with cyan and purple accents to improve visual consistency and readability.

## 📈 Key Analytical Areas

The project examines the following business questions:

1. How are customers distributed across the five clusters?
2. How does average income differ between customer segments?
3. Which customer segments have higher average spending?
4. How does purchase recency vary across clusters?
5. How can customer spending and purchasing patterns inform targeted marketing strategies?

The answers should be derived from the actual cluster results and dashboard values rather than assumed in advance.

## 💡 Business Applications

Customer segmentation can help businesses:

- Develop targeted marketing campaigns for different customer groups.
- Identify customer segments with higher spending levels.
- Tailor promotional offers based on purchasing behavior.
- Understand differences in customer engagement and purchase recency.
- Support customer retention and relationship management strategies.

These are potential applications of the analysis, not measured business outcomes from a live marketing campaign.

## 🚀 How to Run the Project

### Prerequisites

Install Python and the required libraries. Jupyter Notebook is recommended for running the analysis.

### Step 1: Clone the Repository

```bash
git clone https://github.com/Sinchan-hub/Customer-Segmentation-Analytics.git
cd Customer-Segmentation-Analytics
```

### Step 2: Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### Step 3: Install Dependencies

If a `requirements.txt` file is included:

```bash
pip install -r requirements.txt
```

Otherwise, install the libraries required by your notebook, for example:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Step 4: Run the Notebook

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the project notebook and run the cells in sequence.

### Step 5: Open the Power BI Report

Open the `.pbix` file using Microsoft Power BI Desktop. Ensure the dataset path is correctly configured if Power BI requests that you locate the source file.

*Replace the repository URL, notebook name, and dataset filename if your actual project uses different names.*

## 📁 Repository Structure

```text
Customer-Segmentation-Analytics/
│
├── customer_segmentation.ipynb
├── customer_segmentation_powerbi.csv
├── customer_segmentation.pbix
├── requirements.txt
├── README.md
│
└── screenshots/
    ├── overview.png
    └── customer_segment_analysis.png
```

The structure above is a suggested organization. Keep only the files that actually exist in your repository and rename the notebook or report entries to match your filenames.

## 🔮 Future Enhancements

- Evaluate clustering quality using appropriate metrics such as the Silhouette Score.
- Compare different values of K to assess the number of clusters.
- Develop detailed profiles and business recommendations for each cluster.
- Add additional interactive filters and drill-through analysis in Power BI.
- Explore customer lifetime value and campaign response patterns where the available data supports them.

## 👩‍💻 Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Unsupervised Machine Learning
- K-Means Clustering
- Python Data Analysis
- Power BI Dashboard Development
- Data Visualization
- Business Intelligence
- Analytical Problem-Solving

## 📌 Conclusion

This project demonstrates how customer data can be analyzed using Python and machine learning to identify customer segments and explore differences in purchasing behavior. The Power BI dashboard presents these findings through interactive visualizations, helping make the analysis easier to interpret and use for business decision-making.

---

**Technologies:** Python | Pandas | NumPy | Scikit-learn | Jupyter Notebook | Power BI | DAX

**Project Type:** Data Analytics / Machine Learning / Business Intelligence
