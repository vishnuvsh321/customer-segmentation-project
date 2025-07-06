# Customer Segmentation Project

This project focuses on segmenting customers using unsupervised learning techniques to identify groups with similar behaviors and demographics. The objective is to help businesses tailor their marketing strategies by understanding different customer profiles.

## 📁 Project Structure

- `customer_behaviour_data.csv` - Raw dataset containing customer demographics and behavior.
- `customer_segementation_project.ipynb` - Jupyter Notebook with all the preprocessing, clustering, analysis, and visualizations.
- `summary_of_findings.pdf` - A summarized report of key insights and clustering outcomes.

## 📊 Dataset Overview

The dataset includes the following features:
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

There are no missing values in the dataset.

## ⚙️ Methodology

1. **Data Preprocessing**
   - One-hot encoding for `Gender`
   - Feature scaling for `Age`, `Annual Income`, and `Spending Score`

2. **Clustering Technique**
   - K-Means clustering algorithm
   - Optimal number of clusters determined using the Elbow method
   - Visualized using 2D and 3D scatter plots

3. **Cluster Profiles**
   - **Cluster 0**: High income, high spending, balanced gender
   - **Cluster 1**: Older, moderate income/spending, slightly more female
   - **Cluster 2**: Young, low income, high spending, mostly female
   - **Cluster 3**: High income, low spending, slightly more male
   - **Cluster 4**: Young, moderate income/spending, mostly female

## 📌 Key Insights

- The segmentation enables businesses to personalize marketing campaigns based on spending behavior, age, and income.
- High-income, high-spending customers can be prioritized for premium offerings.
- Young high-spending customers on lower incomes may respond well to budget-friendly promotions.

## 📈 Visualizations

- 2D and 3D scatter plots illustrate customer clusters clearly.
- Dimensions used: `Annual Income`, `Spending Score`, and `Age`.

## 🔍 Next Steps

- Collect transaction-level data to perform more advanced RFM (Recency, Frequency, Monetary) analysis.
- Use the current segmentation to design A/B testing for targeted ads and offers.

## 🧠 Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 📬 Contact

For questions or suggestions, feel free to open an issue or submit a pull request!

---

**Author**: Vishnu B  

