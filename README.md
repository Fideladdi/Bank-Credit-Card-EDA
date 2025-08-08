# Bank Credit Card EDA

## 📌 Objective
Analyze customers' transactions and credit profiles to identify a **target group** for the launch of the AtliQo Bank credit card.

## 📂 Dataset
The dataset contains customer demographic details, credit history, and transaction patterns.  
Key columns include:
- `Age`
- `Annual Income`
- `Spending Score`
- `Credit Utilization`
- `Number of Transactions`
- `Default History`

## 🛠 Steps in the EDA
1. **Data Import & Inspection**
   - Loaded dataset into Pandas DataFrame
   - Checked data types, column info, and basic statistics

2. **Data Cleaning**
   - Detected anomalies such as:
     - Minimum age of **1** year (invalid)
     - Annual income of **0** (likely missing or incorrect data)
   - Handled missing values and outliers

3. **Exploratory Analysis**
   - Distribution plots for key features
   - Correlation matrix to identify relationships between variables
   - Segment-wise spending and income analysis

4. **Customer Segmentation**
   - Grouped customers based on income, age, and spending behavior
   - Identified potential target groups for credit card launch

5. **Key Insights**
   - Certain age-income segments show higher spending potential
   - Outliers in credit utilization indicate risk factors
   - Transaction frequency strongly correlates with spending score

## 📈 Visualizations
- Histograms & KDE plots for demographic and financial variables
- Boxplots for income vs. spending
- Heatmap for correlation analysis
- Segmentation bar charts

## 🧰 Tech Stack
- **Python**: Pandas, NumPy, Matplotlib, Seaborn
- **Jupyter Notebook**

