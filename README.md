# 🌸 K-Nearest Neighbors (KNN) Classification on Iris Dataset  

## 📌 Overview  
This project applies **K-Nearest Neighbors (KNN)** on the Iris dataset to classify flower species. It demonstrates instance-based learning, the impact of feature scaling, and the effect of varying K values on classification performance.  

---

## 🔧 Tools & Libraries  
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 📊 Project Workflow  
1. **Dataset Loading** – Loaded Iris dataset from Kaggle.  
2. **Preprocessing** – Removed unnecessary columns and normalized features with `StandardScaler`.  
3. **Model Training** – Implemented KNN using different values of `k`.  
4. **Evaluation** – Measured accuracy, confusion matrix, and classification report.  
5. **Visualization** – Plotted accuracy vs. K and decision boundaries for 2D features.  

---

## 📈 Results  
- Achieved high accuracy (best around **K = optimal value from notebook**).  
- Normalization improved distance-based performance.  
- Decision boundary plots show clear separation between Iris species.  

---

## 🧠 Key Learnings  
- Why **feature scaling** is critical for KNN.  
- How **K selection** affects bias-variance tradeoff.  
- KNN’s ability to handle **multi-class classification**.  
- Influence of **distance metrics** on results.  

---

## 📂 Screenshots
- Accuracy V/S K
- <img width="883" height="690" alt="Screenshot 2025-09-30 193102" src="https://github.com/user-attachments/assets/a9802610-904a-49a7-baa6-f91fe5fbad98" />

- Decision Boundary
- <img width="1039" height="814" alt="Screenshot 2025-09-30 193129" src="https://github.com/user-attachments/assets/77b7acb0-d5e8-42dd-819b-5a7381d9a2dc" />

---

## 🚀 How to Run  
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/KNN-Iris-Classification.git
   cd KNN-Iris-Classification

2.pip install -r requirements.txt

3.jupyter notebook knn_classification.ipynb

