# 🪸 Coral Image Classification

This project focuses on classifying coral images into two categories: **healthy corals** and **bleached corals**. Various machine learning models are trained after extensive preprocessing and augmentation to improve classification performance.

---

## 📂 Dataset

The dataset includes coral images categorized into:
- `healthy_corals/`
- `bleached_corals/`

Images are resized, preprocessed, and augmented to create a robust training set.

---

## 🛠️ Installation

To run this project, make sure the following Python libraries are installed:

pip install numpy pandas matplotlib seaborn scikit-learn opencv-python Pillow tqdm


## 🧼 Image Preprocessing

Each image undergoes the following preprocessing steps:

- 🔄 **Resizing**: All images resized to **64×64 pixels** for consistency and reduced computation.
- 📉 **Duplicate Removal**: Duplicate files detected and deleted to avoid bias.
- 🔁 **Augmentation**: Applied transformations like mirroring and rotation to increase dataset diversity.
- 🌑 **Grayscale Conversion**: Reduced color complexity to focus on structure.
- 🎛️ **Contrast & Brightness Adjustment**: Enhanced visibility and balance across images.

---

## 🤖 Models and Hyperparameter Tuning

We trained and optimized the following models using **GridSearchCV**:

- ✅ **Support Vector Machine (SVM)**
- ✅ **Random Forest**
- ✅ **K-Nearest Neighbors (KNN)**
- ✅ **Logistic Regression**

---

## 📏 Evaluation Metrics

The models were evaluated on:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**

---

## 📊 Results

Each model’s performance (including accuracy and precision) is printed during execution.  
You can use this information to compare models and select the best one for your coral classification task.

---

## 📌 Conclusion

The best-performing model can be selected based on validation scores and metric comparisons.

✅ Proper image preprocessing and augmentation significantly improved the model's ability to distinguish between **healthy** and **bleached** coral.
