# handwriting-recognition-using-k-terms
# 🔢 Digit Classification with KMeans Clustering

This project demonstrates how to use **KMeans clustering** from `scikit-learn` to group handwritten digits from the `digits` dataset and predict clusters for new samples. It includes data visualization, centroid plotting, and label prediction using unsupervised learning.

---

## 📦 Technologies Used

- Python 3.9+
- NumPy
- Matplotlib
- Scikit-learn
- codecademylib3_seaborn (Codecademy environment)

---

## 📚 Dataset

The [`digits` dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html) is a collection of 1,797 grayscale 8x8 images of handwritten digits (0–9) with associated labels.

Each image is flattened into a 64-dimensional vector (8x8 pixels) for modeling.

---

## 🚀 Features Implemented

### ✅ Load and Explore the Data
- Uses `datasets.load_digits()` from `sklearn`
- Prints `digits.target` values
- Displays a sample image from the dataset using `matplotlib`

### ✅ Build and Train KMeans Model
- Applies `KMeans(n_clusters=10)` to cluster the digits into 10 groups
- Trains on all 64-pixel features (`digits.data`)

### ✅ Visualize Cluster Centers
- Displays each cluster center as an 8x8 image (the centroid digit representation)
- Uses a 2x5 subplot grid

### ✅ Predict New Samples
- New 8x8 digit images (flattened into 64 features) are clustered
- Outputs the most likely digit using a manual label-mapping strategy

---

## 📷 Example Output

Sample image preview:
