# **BoostNet-LR-Forecasting-and-Scheduling-Building-Load-through-Real-Time-Occupant-Count-Data**
## Abstract
The smart buildings’ load forecasting is necessary for efficient energy management and it is easily possible because of the data availability based on widespread use of Internet of Things (IoT) devices and automation systems. The information of buildings’ occupancy is directly associated with energy consumption. Therefore, we present a hybrid model consisting of a Long Short-Term Memory (LSTM) network, Extreme Gradient Boosting (XgBoost), Random Forest (RF) and Linear Regression (LR) for commercial and academic buildings’ load forecasting. The correlation between occupants’ count and total load of the building is calculated using Pearson Correlation Coefficient (PCC). The comparative analysis of the proposed approach with LSTM, XgBoost, RF and Gated Recurrent Unit (GRU) is also performed. Root Mean Square Error (RMSE), Mean Absolute Error (MAE), Mean Square Error (MSE) and Normalized Root Mean Square Error (NRMSE) are used as performance indicators for evaluating performance. Findings indicate that the proposed hybrid approach outperforms other models. The RMSE and MAE of 2.99 and 2.18, respectively, are recorded by the proposed model for commercial building dataset while for academic building the RMSE and MAE are 4.48 and 2.85, respectively. Occupancy and load consumption have a positive correlation as evident from PCC analysis. Therefore, we have scheduled the forecasted load based on occupancy patterns for two different cases. Cost is reduced by 17.42% and 33.40% in case 1 and case 2, respectively. Moreover, the performance of the proposed hybrid approach is compared with different techniques presented in literature for buildings load forecasting.

# Getting Started
Follow the steps below to set up and run the code the project.

## Prerequisites
Ensure you have the following software installed:<br>
- Python 3.10.9 or above<br>

Required libraries: <br>
 -  NumPy<br>
 -  Pandas<br>
 -  Scikit-learn<br>
 -  CatBoost<br>
 -  Matplotlib<br>
 -  Seaborn<br>
 -  TensorFlow<br>
 -  Keras<br>
 -  RandomForest<br>

# Running the Code
## Step 1: Data Preprocessing
Run PCC.ipynb script to perform correlation analysis.<br>

## Step 2: Model Training and Evaluation

Run the BoostNet-LR.ipynb, GRU.ipynb, LSTM.ipynb, xgboost.ipynb and rf.ipynb scripts from Models folders to train and evaluate the proposed technique against benchmark techniques.

## Step 3: Visualization
Run the PSO optimization.ipynb, load scheduling case 1.ipynb and load scheduling case 2.ipynb scripts to for occupancy based load scheduling.

Short-term-Global-Horizontal-Irradiance-Forecasting/ <br>
├── Datasets/                   # Folder for datasets <br>
├── Models/                     # Folder containing scripts for model training and evaluation <br>
├── Load optimization             # Folder containing scripts for load scheduling with occupant count data <br>
├── README.md                   # Project README file <br>
## Reference
Please cite this work as:
Rafiq, I., Mahmood, A., Ahmed, U. et al. A Novel Approach for Forecasting and Scheduling Building Load through Real-Time Occupant Count Data. Arab J Sci Eng (2024). https://doi.org/10.1007/s13369-024-09296-9
