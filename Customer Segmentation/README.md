# 🧠 Customer Segmentation using KMeans Clustering

This project performs customer segmentation using **KMeans Clustering** based on customer income and spending score. It identifies distinct customer groups to help businesses understand customer behavior and target them more effectively.

## 📁 Dataset

The dataset used is `Mall_Customers.csv`, which includes:

- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1–100)`

## 📌 Project Workflow

1. **Import Libraries**  
   - numpy, pandas, seaborn, matplotlib  
   - sklearn.cluster (KMeans)

2. **Data Exploration & Cleaning**
   - Loaded the dataset using `pandas.read_csv()`
   - Checked for missing values
   - Visualized basic statistics and distributions

3. **Feature Selection**  
   Selected features:
   ```python
   X = customer_data.iloc[:, [3, 4]].values
Finding the Optimal Number of Clusters

Used Elbow Method by plotting Within Cluster Sum of Squares (WCSS)

Model Training

Trained a KMeans model using n_clusters = 5

Fitted and predicted cluster labels

Visualization

Plotted all clusters in a scatter plot

Highlighted cluster centroids

📈 Elbow Graph
Shows the optimal number of clusters by observing the 'elbow point'.

🖼️ Visualization of Clusters
Customers are segmented into 5 groups, visualized based on annual income and spending score, with different colors and centroid markers.

🧰 Tools Used
Python

Jupyter Notebook / VS Code

Libraries: pandas, matplotlib, seaborn, sklearn

📌 How to Run
Clone the repo

Install dependencies using:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter notebook Customer_Segmentation.ipynb


