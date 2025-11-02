

K-Means Customer Segmentation

## **Project Overview**

This project performs **customer segmentation** using the **K-Means clustering algorithm**.
It groups customers into clusters based on features (e.g., age, annual income, spending score), helping businesses understand customer behavior and target marketing strategies more effectively.

---

## **Dataset**

* Source: Replace with your dataset source (e.g., Kaggle, company dataset, or your CSV)
* Features used:

  * `Feature 1` (e.g., Annual Income)
  * `Feature 2` (e.g., Spending Score)
* Number of records: Replace with your dataset size

---

## **Features**

* **Data preprocessing**: Missing value handling, type conversions
* **K-Means Clustering**: Customizable number of clusters
* **Visualization**: Scatter plot showing clusters and centroids
* **Model Saving**: Trained K-Means model saved for future predictions
* **Downloadable output**: Clustered data saved as CSV

---

## **Installation**

1. Clone the repository:

```bash
git clone https://github.com/002SIDDHARTH/Customer_Segmentation_ML_project.git
cd KMeans_Customer_Segmentation
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## **Usage**

### **1. Run Jupyter Notebook**

```bash
jupyter notebook
```

* Open `customer_segmentation.ipynb`
* Run cells step by step to see cluster visualization


## **Model Loading**

```python
import joblib
kmeans = joblib.load('kmeans_model.pkl')
predicted_clusters = kmeans.predict(new_data)
```

---

## **Results**

* Interactive cluster plots
* Clustered dataset saved for analysis (`customer_segments.csv`)
* Example:
  ![Cluster Plot](visuals/cluster_plot.png)

---

## **Tech Stack**

* Python 3.x
* pandas, numpy
* scikit-learn (KMeans)
* matplotlib / seaborn
* Streamlit (optional for deployment)

---

## **Future Work**

* Add more features for better segmentation (e.g., purchase history)
* Deploy as web app with Flask/Django for production
* Compare K-Means with other clustering algorithms (DBSCAN, Hierarchical)

---

## **Author**

* Name: Siddharth A
* LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)
* GitHub: [github.com/yourusername](https://github.com/yourusername)

Do you want me to do that?
