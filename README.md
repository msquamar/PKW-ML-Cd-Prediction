# PKW-ML-Cd-Prediction

This repository provides the source code and models for predicting the coefficient of discharge (Cd) of type-A Piano Key Weirs (PKWs) using multiple machine learning techniques.  
It is developed as part of the research paper: "Application of Machine Learning Models for Predicting the Coefficient of Discharge of Type-A Piano Key Weirs."

# Repository Structure
Cd_New_Predictor.py → GUI tool for predicting Cd using multiple ML models.  
models → Contains individual implementations of ML models:
SVR_Model.py
Random Forest_Model.py
XGBoost_Model.py
SVR+RF_Model.py

# Installation
Clone this repository:
   git clone https://github.com/msquamar/PKW-ML-Cd-Prediction.git
   cd PKW-ML-Cd-Prediction

# Install dependencies
pip install -r requirements.txt

# Run GUI Application 
python Cd_Predictor.py

# Run Individual Models
python models/SVR_Model.py

# Citation
If you use this code in your research, please cite the corresponding paper:
"Application of Machine Learning Models for Predicting the Coefficient of Discharge of Type-A Piano Key Weirs"
