✨ Netflix Show Clustering – Data Science Mini Project
Grouping similar Netflix shows using K-Means Clustering based on genre and duration.

📌 Overview
This project demonstrates the use of unsupervised learning (K-Means) to cluster Netflix shows by their genres and durations. The dataset was cleaned, feature-engineered, encoded, and visualized using Python libraries.

📁 Dataset
Source: Kaggle – Netflix Shows Dataset

Fields used: listed_in (genre), duration, title

🔧 Tech Stack
Python

Pandas, NumPy – data handling

Matplotlib, Seaborn – data visualization

Scikit-learn – StandardScaler, KMeans

🔄 Workflow
Data Cleaning (removing nulls, simplifying genres, numeric duration extraction)

One-hot Encoding for Genre

Feature Scaling with StandardScaler

Clustering using KMeans (k=5)

Cluster visualization with Matplotlib & PCA

📊 Sample Output
(You can include an image of your cluster plot here)


🧠 Learnings
Applied K-Means Clustering on real-world messy data

Practiced feature engineering and one-hot encoding

Understood how duration and genre affect show grouping

Created interpretable visualizations and cluster summaries

🚀 How to Run
Clone this repo:

git clone https://github.com/yourusername/Netflix_Show_Clustering.git
Create a virtual environment & activate it:

python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate (Windows)
Install dependencies:

pip install -r requirements.txt
Run the notebook:

jupyter notebook netflix_clustering.ipynb
🤝 Contribute
Found a better clustering technique? Feel free to fork and raise a PR!

👩‍💻 Author
Tanishka Jain
Final Year CSE Student | Aspiring Data Scientist
LinkedIn | GitHub

