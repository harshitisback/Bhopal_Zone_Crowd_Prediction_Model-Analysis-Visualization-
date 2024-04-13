# Bhopal_Zone_Crowd_Prediction_Model-Analysis-Visualization-
This Python project analyzes crowd density data in Bhopal, India, and builds machine learning models to predict crowd density based on various factors like weather, time of day, and day of the week. It includes data preprocessing, visualization, model implementation, and evaluation
## Description: 
The provided code is a data analysis and machine learning project implemented in Python using libraries such as numpy, matplotlib, pandas, seaborn, and scikit-learn. The project aims to analyze crowd density data in Bhopal, India, and build machine learning models to predict crowd density based on various factors like weather, time of day, and day of the week.

The code begins with importing necessary libraries and loading the dataset from a CSV file (Bhopal_Crowd_Data.csv). It then proceeds to analyze the dataset by visualizing the distribution of crowd density by zone, weather, hour slot, and day of the week using box plots and bar plots.

Next, it preprocesses the data by encoding categorical variables using label encoding and one-hot encoding techniques. The dataset is split into training and testing sets for model training and evaluation.

Several machine learning models are then implemented and evaluated for crowd density prediction, including Support Vector Machine (SVM), Decision Tree, Multiple Linear Regression, and Random Forest.

The performance of each model is assessed using the R-squared metric, and the best-performing model is used to predict crowd density. Finally, hyperparameter tuning using Grid Search is demonstrated to find the optimal parameters for the Random Forest model.

## Results: 
![image](https://github.com/harshitisback/Bhopal_Zone_Crowd_Prediction_Model-Analysis-Visualization-/assets/77660268/8243b196-14ec-411e-8981-ab9d5f2f3451)
![image](https://github.com/harshitisback/Bhopal_Zone_Crowd_Prediction_Model-Analysis-Visualization-/assets/77660268/b28c8ec5-1aea-482e-aa5d-eeb23b8d89b7)
![image](https://github.com/harshitisback/Bhopal_Zone_Crowd_Prediction_Model-Analysis-Visualization-/assets/77660268/69b43b82-d49f-43d6-b885-fbc27c5f1159)
![image](https://github.com/harshitisback/Bhopal_Zone_Crowd_Prediction_Model-Analysis-Visualization-/assets/77660268/e94d1e60-0af4-4b76-98d2-1d862204a1c6)
![image](https://github.com/harshitisback/Bhopal_Zone_Crowd_Prediction_Model-Analysis-Visualization-/assets/77660268/11c5f742-4fbf-4c87-ab63-bbc9e1d53b16)
![image](https://github.com/harshitisback/Bhopal_Zone_Crowd_Prediction_Model-Analysis-Visualization-/assets/77660268/b8cd9cef-feb9-41aa-bf28-8a1c664f3b4e)


## Prediction Graph
![image](https://github.com/harshitisback/Bhopal_Zone_Crowd_Prediction_Model-Analysis-Visualization-/assets/77660268/d31143c8-4b97-4801-b37b-96e9202fbf11)
## Expanded Graph
![image](https://github.com/harshitisback/Bhopal_Zone_Crowd_Prediction_Model-Analysis-Visualization-/assets/77660268/e5cb0670-dfe0-4863-a902-a4080061a297)

Accuracies-Mean: 88.89%

## Usage:

Clone the repository or download the files.
Run the Caps_Data.ipynb notebook in a Jupyter environment.
## Dependencies:

Python 3.x
Libraries: numpy, matplotlib, pandas, seaborn, scikit-learn
## Contributors:
1.Harshit Tiwari
2.Shashwat Saxena
2.Akshay Mathur
4.Tapesh.
## License:
MIT License

## API Link (to be provided shortly):
API Link

## Note:
Ensure Bhopal_Crowd_Data.csv is in the same directory as the notebook before running the code.





