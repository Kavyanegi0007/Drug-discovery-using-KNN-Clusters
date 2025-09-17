install


pandas
numpy
scikit-learn
matplotlib
seaborn
rdkit-pypi

# Molecular Feature Clustering with DC50 Insights

This project uses PCA and KMeans clustering to analyze molecular features and investigate the distribution of DC50 (half-maximal degradation concentration) values. The aim is to identify patterns among molecules and better understand how known DC50 values cluster in molecular space.
<img width="893" height="502" alt="image" src="https://github.com/user-attachments/assets/dab637d6-d7db-4f26-8b15-f2d2295a9217" />

## 🧪 Objective

- Reduce the dimensionality of molecular feature data using PCA.
- Cluster molecules using KMeans.
- Visualize clusters and overlay known DC50 values.
- Analyze the distribution of DC50 values across clusters.

## 📁 Dataset

The dataset contains molecular features and DC50 values for a subset of compounds. It was used to:
- Generate visualizations of the DC50 distribution
- Create PCA-reduced plots of molecular feature space

## 🧰 Tools & Libraries

- Python
- RDKit for molecular data processing
- Scikit-learn for PCA and KMeans clustering
- Matplotlib & Seaborn for plotting

## 📈 Key Visualizations

- **Distribution of DC50 values**  
  Shows how the known DC50 values are spread across compounds

- **PCA + KMeans Clusters**  
  Reduces molecular features to 2D and highlights clusters with known DC50 values in red circles
<img width="1262" height="596" alt="image" src="https://github.com/user-attachments/assets/4b5906fb-b507-4624-b3c1-0cf6ba8e1279" />

## 🧠 Challenges Faced

- High dimensionality of molecular data required dimensionality reduction
- Imbalanced distribution of known DC50 values made clustering interpretation harder
- Determining an optimal number of clusters was non-trivial

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/dc50-clustering.git
   cd dc50-clustering
