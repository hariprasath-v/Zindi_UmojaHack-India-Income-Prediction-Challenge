# Zindi_UmojaHack-India-Income-Prediction-Challenge

### Competition hosted on <a href="https://zindi.africa/competitions/umojahack-india-2022">zindi.africa</a>

# About

### Create a machine learning model to predict whether an individual earns above 50,000 in a specific currency or not.

### Final Score is 0.613205338

### Leaderboard Rank is 30

### Evaluation Metric is F1 score.

### File information
 
 * zindi-income-prediction-challenge-umojahack-eda.ipynb
    #### Basic Exploratory Data Analysis
    #### Packages Used,
        * seaborn
        * Pandas
        * Numpy
        * Matplotlib
* zindi-income-prediction-challenge-umojahack-model.ipynb
    #### Data Pre-processing and model. 
    #### Packages Used,
        * Sklearn
        * Pandas
        * Numpy
        * Matplotlib
        * catboost    
     #### Created catboost classifier model and evaluate the validation data with f1 score. 
     #### [For more detailed information about the model.](https://github.com/hariprasath-v/Zindi_UmojaHack-India-Income-Prediction-Challenge/blob/main/Approach_Zindi_UmojaHack%20India%20Income%20Prediction%20Challenge.pdf)
     

### Catboost model optimal threshold(0.3862)
![Alt text](https://github.com/hariprasath-v/Zindi_UmojaHack-India-Income-Prediction-Challenge/blob/main/Model%20visualization/Optimal%20threshold%20plot(Optimal%20threshold%200.3862).png)

### Based on the optimal threshold,
#### Train data classification report,
![Alt text](https://github.com/hariprasath-v/Zindi_UmojaHack-India-Income-Prediction-Challenge/blob/main/Model%20visualization/Train%20data%20classification%20report.PNG)

#### Validation data classification report,
![Alt text](https://github.com/hariprasath-v/Zindi_UmojaHack-India-Income-Prediction-Challenge/blob/main/Model%20visualization/Validation%20data%20classification%20report.PNG)

### Catboost – SHAP feature importances
![Alt text](https://github.com/hariprasath-v/Zindi_UmojaHack-India-Income-Prediction-Challenge/blob/main/Model%20visualization/Catboost%20Shap%20-%20feature%20importances%20plot.png)

### Catboost – SHAP top feature importances
![Alt text](https://github.com/hariprasath-v/Zindi_UmojaHack-India-Income-Prediction-Challenge/blob/main/Model%20visualization/Catboost%20Shap%20-%20top%20feature%20impact.png)

### SHAP Feature impact for single observation(class 0)
![Alt text](https://github.com/hariprasath-v/Zindi_UmojaHack-India-Income-Prediction-Challenge/blob/main/Model%20visualization/Shap%20Feature%20impact%20single%20observation%20for%20class%200.png)

### SHAP Feature impact for single observation(class 0)
![Alt text](https://github.com/hariprasath-v/Zindi_UmojaHack-India-Income-Prediction-Challenge/blob/main/Model%20visualization/Shap%20Feature%20impact%20single%20observation%20for%20class%201.png)
