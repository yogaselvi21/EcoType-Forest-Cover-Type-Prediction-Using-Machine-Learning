# EcoType-Forest-Cover-Type-Prediction-Using-Machine-Learning

🌲 EcoType: Forest Cover Type Prediction
📌 Project Overview
This project uses Machine Learning to predict seven different forest cover types based on cartographic variables. It automates the classification of forest patches (30 x 30 meters) in the Roosevelt National Forest of northern Colorado.
🗂️ Project Structure
Mini_project_3_Data_Cleaning.ipynb: Initial data inspection and handling missing values.
Mini_Project_3_Data_Preprocessi...: Feature scaling, encoding, and preparation.
Mini_Project_3_Classification.ipynb: Model training, hyperparameter tuning, and evaluation.
Mini_Project_3_Streamlit.ipynb: Code for the interactive deployment app.
📊 Dataset Features
The model analyzes 54 features, including:
Elevation: Height above sea level.
Aspect: Compass direction of the slope.
Slope: Steeper or flatter terrain.
Wilderness Area: Binary indicator for 4 specific regions.
Soil Type: Binary indicator for 40 specific soil types.
🚀 How to Run
Clone the repo: git clone [your-repo-link]
Install dependencies: pip install -r requirements.txt (Tip: You should create this file!)
Launch the App: streamlit run Mini_Project_3_Streamlit.py
📈 Results
Model Used: Random Forest
Accuracy: [Insert % here]
Key Insight: Elevation was the most significant predictor for cover type.
