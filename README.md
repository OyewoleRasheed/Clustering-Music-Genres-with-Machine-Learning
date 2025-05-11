# 🎶 Clustering Music Genres with Machine Learning

This project replicates the tutorial from [The Clever Programmer](https://thecleverprogrammer.com/2022/04/05/clustering-music-genres-with-machine-learning/)
It clusters music tracks into different genres using **unsupervised machine learning** techniques like **K-Means Clustering**.

---

## 🚀 Features

* Loads and processes a dataset of songs with audio features
* Normalizes data using **MinMaxScaler**
* Uses **K-Means Clustering** to group similar songs
* Visualizes the clusters in 3D scatterplot
* Shows how machine learning can discover genre patterns without explicit labels

---

## 📦 Requirements

Install the necessary Python packages:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

---

## 📊 Workflow

1. **Load Data**

   * Reads the songs dataset containing features like `tempo`, `energy`, `danceability`, etc.

2. **Feature Scaling**

   * Uses **MinMaxScaler** to normalize numeric features between 0 and 1.

3. **Clustering**

   * Applies **K-Means Clustering** to group songs into distinct clusters (genres).
   * Number of clusters (k) is set manually (e.g., `k=10`).

4. **Visualization**

   * Plots the clusters in 3D scatterplot using **plotly**

---

## 📈 Example Output

* A 3D scatter plot where each color represents a cluster (genre group)
* Songs grouped based on similarity in audio features like  `energy`, and `danceability`

---

## 🔄 Techniques Used

* ✅ `MinMaxScaler` for normalization
* ✅ `KMeans` for clustering
* ✅ `Plotly` 

---

## 📚 References

* Original Tutorial:
  [Clustering Music Genres with Machine Learning — The Clever Programmer (2022)](https://thecleverprogrammer.com/2022/04/05/clustering-music-genres-with-machine-learning/)


---

## 🙋 Author

Replicated and adapted by **Oyewole Rasheed**
Originally inspired by *The Clever Programmer* tutorial.
