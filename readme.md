# K-Means Clustering Learning Project

This repository contains my experiments and learning notes while exploring **K-Means Clustering**, a popular unsupervised machine learning algorithm.  

The goal of this repo is to:  
- Understand how K-Means works step by step  
- Practice scaling and fitting data before clustering  
- Visualize clusters and centroids in 2D  
- Experiment with different numbers of clusters (`k`)  
- Build intuition for how Euclidean distance and scaling affect results  

---

## 📂 Repository Structure

├── data/         # Sample datasets (if any)
├── notebooks/    # Jupyter notebooks with experiments
├── images/       # Saved plots of clusters
├── src/          # Python scripts for reusable code
└── README.md     # Project documentation



---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/kmeans-learning.git
cd kmeans-learning
```


### 2. Create a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate   # for Mac/Linux
venv\Scripts\activate      # for Windows
```

### 3. Install dependencies
```bash
uv sync
```

Example requirements.txt:
```bash
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

## 📊 Example Visualization

Here’s an example of clustering **Annual Income vs Spending Score** using K-Means:

- Brown, Red, Yellow, Blue, Green → different clusters  
- ⭐ (red star) → cluster centroids  

---

## 🧠 What I Learned

- **Scaling matters**: features with larger ranges dominate distance calculations if not normalized.  
- **Fit vs Transform**:  
  - `scaler.fit(X)` learns mean & std  
  - `scaler.transform(X)` applies scaling  
  - `kmeans.fit(X)` learns cluster centroids  
- **Euclidean distance** is the heart of K-Means, so feature magnitudes are critical.  
- **Choosing k**: explored methods like the **Elbow Method** and **Silhouette Score**.  

---

## 🔮 Next Steps

- Try clustering on higher-dimensional datasets (more than 2 features).  
- Explore different distance metrics (Manhattan, cosine).  
- Compare K-Means with other clustering algorithms (DBSCAN, Hierarchical).  

---

## ⚡ Tech Stack

- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- scikit-learn  

---

✍️ *This project is purely for learning purposes as I build intuition and practice clustering techniques.*  






