🌸 K-Nearest Neighbors (KNN) Classification on Iris Dataset
📌 Overview

This project demonstrates K-Nearest Neighbors (KNN) classification using the classic Iris dataset. The goal is to explore how instance-based learning works, understand the role of distance metrics, and evaluate model performance across different values of K.

🔧 Tools & Libraries

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

📊 Project Workflow

Dataset Loading – Iris dataset from Kaggle.

Preprocessing – Removed unnecessary columns and normalized features using StandardScaler.

Model Training – Implemented KNN with varying k values.

Evaluation – Measured accuracy, confusion matrix, and classification report.

Visualization – Plotted accuracy vs. K and decision boundaries for 2D features.

📈 Results

Best accuracy achieved around K = (check results in notebook).

Decision boundary plots highlight the separation between Iris species.

Normalization significantly improved distance-based classification performance.

🧠 Key Learnings

Importance of feature scaling in distance-based algorithms.

Trade-off in selecting K (small K → sensitive to noise, large K → smoother boundary).

KNN works naturally for multi-class classification.

Distance metric choice impacts results.
