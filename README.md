# 🎵 Music Genre Classification with PCA

This project focuses on **classifying music genres** using **Machine Learning techniques** with **Principal Component Analysis (PCA)** for dimensionality reduction.  
It demonstrates data preprocessing, feature extraction, dimensionality reduction, and classification using supervised learning models.

---

## 📌 Project Overview
Music genre classification is a classic problem in the field of **Music Information Retrieval (MIR)**.  
In this project, we:
- Preprocess and clean the dataset.  
- Apply **PCA** to reduce feature dimensions while retaining maximum variance.  
- Train classification models on reduced dimensions.  
- Evaluate performance using accuracy and visualizations.  

---

## 📂 Project Structure
```
├── Music Genre Classification with PCA - Project.ipynb   # Main Jupyter Notebook
├── data/                                                 # Dataset folder (if applicable)
├── models/                                               # Trained model files (optional)
└── README.md                                             # Project documentation
```

---

## ⚙️ Requirements
Make sure you have the following installed:

```bash
python 3.8+
numpy
pandas
matplotlib
seaborn
scikit-learn
```

Install them using:
```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run
1. Clone this repository or download the files.  
2. Place the dataset in the `data/` folder.  
3. Open the notebook:
   ```bash
   jupyter notebook "Music Genre Classification with PCA - Project.ipynb"
   ```
4. Run all cells sequentially to reproduce results.  

---

## 🔑 Key Steps
1. **Data Preprocessing**  
   - Handle missing values.  
   - Normalize feature values.  

2. **Dimensionality Reduction with PCA**  
   - Reduce high-dimensional feature space.  
   - Retain top principal components that capture maximum variance.  

3. **Model Training & Evaluation**  
   - Train classifiers (e.g., Logistic Regression, Random Forest, SVM).  
   - Compare accuracy before and after PCA.  
   - Evaluate using confusion matrix & classification reports.  

4. **Genre Prediction for Unknown Data**  
   - Apply trained classifier to predict missing/unknown genres.  

---

## 📊 Results
- PCA reduced dimensionality significantly while preserving performance.  
- Visualization of clusters shows genre separation.  
- Classifier accuracy improved with optimized features.  

---

## 📌 Future Work
- Experiment with **deep learning models (CNNs, RNNs)**.  
- Use **spectrograms and raw audio features** for classification.  
- Apply **hyperparameter tuning** for better accuracy.  

---

## ✨ Author
Developed by **Md Redwan Hossain** as part of a machine learning project on **Music Genre Classification**.
