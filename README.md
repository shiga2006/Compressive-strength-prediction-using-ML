🏗️ Compressive Strength & 🌱 CO₂ Emission Prediction
Smart Material Property Prediction using Machine Learning

📌 Overview
In this project, we predict the compressive strength of materials and estimate the CO₂ emissions during production using CatBoost with Optuna-based hyperparameter optimization.

Why?

Material engineers need accurate strength predictions to ensure safety and efficiency.

Environmental researchers require CO₂ emission estimation for sustainable production.

Our model aims to help manufacturers, researchers, and decision-makers make data-driven and eco-conscious choices.

🚀 Features

✅ Predicts Compressive Strength of materials

✅ Estimates CO₂ emissions during production

✅ Uses CatBoost for superior accuracy

✅ Optuna for hyperparameter optimization

✅ Clean & reproducible code

✅ Easy-to-use for both research and industry applications


🧠 Methodology

1️⃣ Dataset Preprocessing

    - Missing value handling

    - Outlier detection & removal

    - Feature scaling & encoding


2️⃣ Model Selection

    - Chose CatBoost for its handling of categorical data, robustness, and interpretability


3️⃣ Model Training

    - Separate models for Compressive Strength and CO₂ Emission prediction

    - Train-test split & cross-validation



4️⃣ Model Optimization (Optuna)

    - Hyperparameters like depth, learning_rate, iterations tuned for best performance

    - Objective function maximizes model accuracy while minimizing RMSE


📊 Results

  Compressive Strength Model → High R² score (>0.9)


  CO₂ Emission Model → Accurate estimation within low error margins


  Optimized models outperform default CatBoost settings

📂 Project Structure

📦 compressive-strength-co2-prediction

 ┣ 📜 data/                # Dataset files
 
 ┣ 📜 notebooks/           # Jupyter notebooks for analysis
 
 ┣ 📜 src/                 # Main source code
 
 ┃ ┣ model_training.py     # Model training logic
 
 ┃ ┣ optimize_model.py     # Optuna optimization
 
 ┣ 📜 requirements.txt     # Dependencies
 
 ┣ 📜 README.md            # Project README


🛠️ Tech Stack

   Python 🐍

   CatBoost 📈

   Optuna ⚙️

   Pandas, NumPy, Matplotlib, Seaborn


📦 Installation & Usage
# Clone the repository
git clone [https://github.com/yourusername/compressive-strength-co2-prediction.git](https://github.com/shiga2006/Compressive-strength-prediction-using-ML)

# Run training
comparison-4 models.ipynb

# Run optimization
CatBoost optimization.ipynb


📌 Future Improvements

🔹 Add SHAP explainability for feature importance

🔹 Include real-time prediction API

🔹 Expand dataset for global applicability


🤝 Contributing
Pull requests are welcome! If you have ideas to make this better, please fork the repo and submit a PR.



