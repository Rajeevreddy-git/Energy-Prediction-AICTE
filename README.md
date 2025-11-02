# Energy-Prediction-AICTE
# Electric Vehicles energy consumption prediction

This project uses machine learning to predict how much energy an electric vehicle (EV) will consume during a trip. It helps EV users estimate battery usage based on trip distance, speed, road type, and weather conditions. The goal is to improve route planning and reduce range anxiety.

# Objectives
1. Predict EV energy consumption (in kWh) for daily routes
2. Use simple ML models like Linear Regression or Decision Tree
3. Help users plan charging and optimize travel efficiency

# Dataset
The dataset contains information related to trips taken by electric vehicles, including:
1. Trip Distance
2. Time of Day
3. Current
4. Maximum Cell Temperature of Battery
5. Trip Time Length
6. Trip Energy Consumption

These features are used to predict the energy consumption during each trip.

# Model Used
This project uses the Gradient Boosting Regressor, a machine learning model known for its accuracy in predicting continuous values. It was trained on EV trip data to estimate how much energy (in kWh) an electric vehicle will consume during a journey.

# Workflow Summary
1. 	Data Preprocessing
Cleaned and normalized the dataset to ensure consistent and reliable inputs.
2. 	Feature Selection
Chose key features like trip distance, speed, elevation, and weather conditions that influence energy usage.
3. 	Model Training
Trained the Gradient Boosting Regressor using selected features and the target variable (energy consumption).
4. 	Prediction
The model can now estimate energy usage for new trip inputs, helping users plan EV charging more effectively

# How to Use
Use the get_prediction() function to enter trip details and receive an energy estimate.
To run the project:
1. 	Download or clone the repository.
2. 	Install dependencies: pip install -r requirements.txt.
3. 	Run the script and input trip parameters to get predictions.# Energy-Prediction-AICTE
EV Power Usage Predictor
