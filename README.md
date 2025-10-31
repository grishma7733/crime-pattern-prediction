🕵️‍♀️ Crime Type Prediction using Machine Learning

Predicts the type of crime (Theft, Hit & Run, Assault, Kidnapping, Murder) based on date, time, and location (latitude & longitude) using Python and Machine Learning models.

🚀 Overview

This project analyzes real-world crime data to identify patterns and predict the most probable type of crime at a given time and place.
It combines data preprocessing, feature engineering, and ML models to achieve over 98% accuracy.

🧾 Features

✅ Clean and preprocess raw crime data
✅ Extract time-based features (year, month, day, hour, etc.)
✅ Visualize data using Seaborn and Matplotlib
✅ Train ML models (KNN & Decision Tree)
✅ Predict crime type for new unseen data

📊 Dataset Information
Column	Description
timestamp	Date and time of the incident
Theft	1 if theft occurred, else 0
Hit and run	1 if hit & run occurred, else 0
Assault	1 if assault occurred, else 0
Kidnapping	1 if kidnapping occurred, else 0
Murder	1 if murder occurred, else 0
latitude	Crime location latitude
longitude	Crime location longitude
🧠 Machine Learning Models Used
Model	Description	Accuracy
KNN (K-Nearest Neighbors)	Classifies crimes based on closest known patterns	🟢 98.3%
Decision Tree	Builds a tree of decisions to classify the crime type	🟢 98.0%

The KNN model was chosen as the final predictor for its higher accuracy and stability.

⚙️ Tech Stack

🐍 Python

🧮 NumPy

📊 Pandas

📉 Matplotlib & Seaborn

🤖 Scikit-learn

💻 How to Run

Open this notebook in Google Colab or Jupyter Notebook.

Upload the dataset file data.csv to your working directory.

Run all code cells in order.

Try your own prediction using:

predict([[2017, 2, 28, 8, 22.722247, 75.915294]])


Output:

Crime Type: [[0 0 0 1 0]]
Predicted crime type is: Kidnapping

📈 Visualizations

KDE Plots – Show crime type density

Hexbin Plot – Displays relation between crime types and time of day

Feature Trends – Understand patterns based on hours, days, and months

🔮 Future Improvements

Integrate Google Maps API for location visualization

Add weather and demographic features for deeper insights

Build a Streamlit or Flask web app for real-time predictions

👩‍💻 Author

Grishma Naik
💬 Data Science & Machine Learning Enthusiast
📍 Passionate about building smart, data-driven solutions
