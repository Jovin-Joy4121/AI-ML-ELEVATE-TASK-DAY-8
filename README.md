# 🛍️ Mall Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to group mall customers based on their demographics and spending behavior.

## 📊 Objective

To perform unsupervised learning using **K-Means clustering** and segment customers into distinct groups for targeted marketing and analysis.

---

## 📁 Dataset

**Mall_Customers.csv**  
- 200 entries  
- Features:  
  - `CustomerID` (removed)
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🧠 Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 🧪 Steps Performed

1. **Loaded** the dataset and cleaned unnecessary columns.
2. **Converted** categorical `Gender` into numeric format.
3. **Reduced** dimensions using PCA for better visualization.
4. **Used** the **Elbow Method** to determine the optimal number of clusters.
5. **Applied** the K-Means algorithm with `k = 5`.
6. **Visualized** clusters using PCA-reduced 2D space.
7. **Evaluated** model performance using **Silhouette Score**.

---

## 📷 Visualizations

- Elbow Plot to determine the best number of clusters.
- 2D PCA scatter plot with color-coded clusters.

---

## 📈 Results

- **Optimal Clusters (k):** 5 (based on Elbow method)
- **Silhouette Score:** ~0.44 (indicates moderate clustering quality)

---

## 📂 How to Run

1. Open the notebook in **Google Colab**
2. Upload the `Mall_Customers.csv` file when prompted
3. Run all cells to see the clustering and visual output

---

## ❓ Interview Questions Covered

- How does K-Means clustering work?
- What is the Elbow method?
- What is Silhouette Score?
- What are the limitations of K-Means?
- How does initialization affect K-Means results?
- What's the difference between clustering and classification?

---

## 🔗 Submission

After pushing to GitHub, submit the repository link using the provided internship submission form.

✅ Example: [https://github.com/your-username/kmeans-mall-customers](https://github.com/your-username/kmeans-mall-customers)

---

## 🧑‍💻 Author

This project was completed as part of the **AI & ML Internship Task 8**.

