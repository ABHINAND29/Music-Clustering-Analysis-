# Music-Clustering-Analysis-
The goal of this project was to group songs into meaningful clusters based on their audio features such as danceability, energy, tempo, acousticness, and valence. This helps in understanding different types of music and enables applications like recommendation systems
# 🎧 Music Clustering Analysis using Machine Learning

## 📌 Overview

This project applies **unsupervised machine learning** techniques to group songs based on their audio features. The goal is to identify patterns in music and categorize tracks into meaningful clusters such as *party*, *chill*,  *happy* and *melody* songs.

---

## 🎯 Objectives

* Analyze audio features of songs
* Group similar songs using clustering algorithms
* Visualize and interpret clusters
* Enable applications like music recommendation systems

---

## 📂 Dataset

The dataset contains audio features of songs such as:

* Danceability
* Energy
* Loudness
* Speechiness
* Acousticness
* Instrumentalness
* Liveness
* Valence
* Tempo
* Duration

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 🔍 Methodology

### 1. Data Preprocessing

* Removed unnecessary columns (track name, artist, ID)
* Handled missing values
* Scaled features using **StandardScaler**

---

### 2. Feature Selection

Selected relevant audio features for clustering:

```python
features = [
    'danceability','energy','loudness','speechiness',
    'acousticness','instrumentalness','liveness',
    'valence','tempo'
]
```

---

### 3. Dimensionality Reduction (Optional)

* **PCA** for visualization
* **t-SNE** for better cluster separation

---

### 4. Clustering Techniques

#### 🔹 K-Means Clustering

* Applied K-Means algorithm
* Determined optimal clusters using:

  * **Elbow Method (WCSS)**
  * **Silhouette Score**

#### 🔹 Hierarchical Clustering (Optional)

* Used dendrogram for visualizing cluster formation

---

### 5. Evaluation

* **Silhouette Score** to measure cluster quality
* Visualization using PCA / t-SNE

---

## 📊 Results

### 🔸 Cluster 0 – Party Tracks

* High energy and danceability
* Fast tempo
* Upbeat songs

### 🔸 Cluster 1 – Chill Acoustic

* High acousticness
* Low energy
* Relaxing songs

### 🔸 Cluster 2 – Happy / Balanced

* Moderate energy
* High valence
* Feel-good songs

### 🔸 Cluster 3 – Melody

* Moderate energy
* High valence
* Feel-good songs
---

## 📈 Visualizations

* PCA / t-SNE scatter plots
* Heatmaps of feature importance
* Bar charts of cluster averages
* Distribution plots (KDE, Box, Violin)

---

## 🚀 Applications

* Music recommendation systems
* Playlist generation
* Mood-based song categorization
* Music analytics

---

## ⚠️ Limitations

* Some overlap between clusters
* K-Means assumes spherical clusters
* Results depend on selected features

---

## ✅ Conclusion

The clustering model successfully groups songs into meaningful categories based on audio features. These insights can be used in real-world applications like recommendation systems and music discovery platforms.

---

## 📁 Output

* Clustered dataset exported as CSV
* Each song assigned a cluster label

---

## 🔮 Future Improvements

* Incorporate genre/lyrics features
* Build a real-time recommendation system
* Deploy using Streamlit

---

## 🙌 Author

**Abhinand KM**
Diploma in Computer Engineering
Specialized in Python Django

---

