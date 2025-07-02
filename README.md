✨ Netflix Show Clustering – Data Science Mini Project
Grouping similar Netflix shows using K-Means Clustering based on genre and duration.

📌 Overview
This project demonstrates the use of unsupervised learning (K-Means) to cluster Netflix shows based on their genre and duration. The dataset was cleaned, processed, feature-engineered, and visualized using popular Python data science libraries.

📁 Dataset
Source: Kaggle – Netflix Shows Dataset

Fields Used: listed_in (genre), duration, title

🔧 Tech Stack
Python

Pandas, NumPy – for data handling

Matplotlib, Seaborn – for data visualization

Scikit-learn – for StandardScaler and KMeans clustering

🔄 Workflow
Data Cleaning

Removed null values

Extracted numeric duration from strings

Simplified multi-genre entries

One-Hot Encoding for genre

Feature Scaling with StandardScaler

Clustering using KMeans (with k=5)

Visualization using Matplotlib and PCA for 2D cluster plotting


🧠 Learnings
Applied K-Means Clustering on real-world, messy data

Practiced feature engineering and one-hot encoding

Understood how duration and genre influence show grouping

Created interpretable visualizations and cluster summaries

🤝 Contribute
Have a better clustering approach or visualization idea?
Feel free to fork this repo and raise a PR! Suggestions are always welcome.

