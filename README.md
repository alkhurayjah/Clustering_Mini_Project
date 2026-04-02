# 🧠 Clustering Mini Project — Customer Segmentation

## 📌 Overview
This project applies and compares multiple clustering algorithms on the **Mall Customers Dataset** to understand customer behavior and identify meaningful segments based on purchasing patterns.

The goal is to evaluate how different clustering techniques perform and determine the most suitable approach for customer segmentation.

---

## 👥 Team Members
- Faisal  
- Lana  
- Alaa  
- Abdullah  

---

## 📊 Dataset
We used the **Mall Customers Dataset**, which contains information about customers such as:

- Age  
- Gender  
- Annual Income (k$)  
- Spending Score (1–100)  


---

## ⚙️ Project Workflow

### 1️⃣ Data Preparation
- Removed irrelevant features (`CustomerID`)
- Checked for missing values and duplicates (none found)
- Applied **encoding** to categorical variable (Gender)
- Performed **feature scaling** using `StandardScaler`

---

### 2️⃣ Clustering Algorithms Applied
We implemented and compared the following algorithms:

- 🔹 K-Means Clustering  
- 🔹 DBSCAN  
- 🔹 Hierarchical Clustering (Agglomerative)  

---

### 3️⃣ Model Evaluation
We used the **Silhouette Score** to evaluate clustering performance:

| Algorithm       | Clusters | Silhouette Score |
|----------------|----------|------------------|
| K-Means        | 5        | 0.4085           |
| Hierarchical   | 5        | 0.3900           |
| DBSCAN         | 8        | 0.4585           |

---

## 📈 Key Insights

- **DBSCAN achieved the highest silhouette score**, indicating better cluster separation.
- However, DBSCAN identified a significant number of **noise points**, which may impact interpretability.
- **K-Means provided more balanced and interpretable clusters**, making it suitable for business applications.
- **Hierarchical Clustering** showed similar behavior to K-Means but slightly lower performance.

---

## 🧠 Conclusion

- From a **numerical perspective**, DBSCAN performed best.
- From a **practical and business perspective**, **K-Means is more reliable and interpretable** for customer segmentation.

---

## 📊 Visualization
The project includes:
- Elbow Method for optimal K selection  
- 2D cluster visualization  
- 3D cluster visualization  
- Clustering comparison chart  



---

## 🚀 Future Improvements
- Apply clustering on larger and real-world datasets  
- Use advanced techniques like **Gaussian Mixture Models (GMM)**  
- Add cluster profiling (mean income, age, etc.)  
- Deploy results in an interactive dashboard  

---

## 🛠️ Technologies Used
- Python 🐍  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

## 📌 How to Run
1. Clone the repository:
```bash
git clone https://github.com/your-username/clustering-project.git
