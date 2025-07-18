🌿 Plant Disease Prediction using Environmental Data

📌 Problem Statement

Plant diseases, especially fungal infections, are a major cause of crop losses globally. These diseases are often triggered by environmental factors like high humidity, temperature, and rainfall. Early prediction of disease outbreaks enables farmers to take preventive actions, optimize pesticide use, and improve crop yield.



This project leverages a Decision Tree Classifier to predict the likelihood of plant disease based on real-time environmental data.



📂 Dataset Overview

The synthetic dataset consists of 10,000 samples simulating diverse environmental conditions across different farm locations. Each sample includes environmental measurements and a binary label indicating plant health.



🔑 Features

temperature — Ambient temperature (°C)

humidity — Air humidity (%)

rainfall — Rainfall (mm)

soil\_pH — Soil pH value

disease\_present — Target label (0 = Healthy, 1 = Diseased)

🎯 Objective

Train a binary classification model using a Decision Tree to predict plant disease presence from environmental factors.



🛠️ Tools \& Technologies

Python

Scikit-learn (DecisionTreeClassifier)

Pandas, NumPy, Matplotlib

Jupyter Notebook

Streamlit (for web UI)

🚀 Getting Started

Follow these steps to set up the project, train the model, and launch the Streamlit app:



1\. Clone the Repository

git clone https://github.com/vinayiet/plant-disease-predictor.git

cd plant-disease-predictor

2\. Create a Virtual Environment

\# Create environment with Python 3.10

conda create --name plant\_env python=3.10



\# Activate the environment

conda activate plant\_env

3\. Install Required Dependencies

pip install -r requirements.txt

requirements.txt should include:



pandas

numpy

scikit-learn

matplotlib

streamlit

4\. Train the Model (Optional)

Run the training script to train the model and export plant\_disease\_detection\_model.pkl: Or, open and run the notebook:



jupyter notebook model.ipynb

5\. Run the Streamlit App

streamlit run app.py

This will open the app in your web browser.



6\. Use the App

Enter environmental parameters in the input fields:



🌡️ Temperature

💧 Humidity

🌧️ Rainfall

🌱 Soil pH

Click "Predict Disease Status" to get a prediction:



✅ Healthy

⚠️ Diseased

🧪 Troubleshooting

If streamlit is not recognized, reactivate your environment.

If plant\_disease\_detection\_model.pkl is missing, ensure train\_model.py ran successfully.

Confirm all libraries from requirements.txt are installed.

📈 Potential Applications

Smart farming platforms

Weather-based plant disease alert systems

Precision agriculture dashboards  

