# EcoType-Forest-Cover-Type-Prediction-Using-Machine-Learning

🌲 EcoType: Forest Cover Type Prediction


📌 Project Overview:

This project uses Machine Learning to predict seven different forest cover types based on cartographic variables. The goal is to assist in environmental monitoring, forestry management, and land use planning by providing automated, reliable forest cover type identification.


🗂️ Project Structure

Mini_project_3_Data_Cleaning.ipynb: Initial data inspection and handling missing values.

Mini_Project_3_Data_Preprocessing.ipynb: Feature scaling, encoding, and preparation.

Mini_Project_3_Classification.ipynb: Model training, hyperparameter tuning, and evaluation.

Mini_Project_3_Streamlit.ipynb: Code for the interactive deployment app.


📊 Dataset Features

The model analyzes 54 features, including:

Elevation: Height above sea level.

Aspect: Compass direction of the slope.

Slope: Steeper or flatter terrain.

Horizontal_Distance_To_Hydrology: The horizontal distance to the nearest surface water features (streams, lakes, etc.).

Vertical_Distance_To_Hydrology: The vertical distance (elevation difference) to the nearest surface water features.

Horizontal_Distance_To_Roadways: The horizontal distance to the nearest roadway.

Horizontal_Distance_To_Fire_Points: The horizontal distance to the nearest wildfire ignition points. 

[Hillshade Indices (0 to 255 index) 
These values represent the amount of shade or sunlight a specific area receives at different times during the summer solstice]

Hillshade_9am: Shade index at 9:00 AM.

Hillshade_Noon: Shade index at 12:00 PM.

Hillshade_3pm: Shade index at 3:00 PM. 

Wilderness Area: Binary indicator for 4 specific regions.

Soil Type: Binary indicator for 40 specific soil types.


📈 Results

Model Used: Random Forest

Accuracy: 94.95%

Key Insight: Elevation was the most significant predictor for cover type.
