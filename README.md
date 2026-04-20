# Human-Behaviour-Predict-KNN
Using KNN to train and test a machine learning model for predicting human-related outcomes or behaviour based on features in dataset.
This project focuses on predicting human-related outcomes using machine learning models. It uses structured datasets (`train_human_predict.csv` and `test_human_predict.csv`) to train and evaluate classification models. The goal is to understand patterns in human data and make accurate predictions based on given features.

**NOTE**: Since the datset was big hence can be reffered from here https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones?resource=download

# Objective
1.Predict human-related outcomes using classification techniques.  
2.Train models using training data.  
3.Evaluate model performance using multiple metrics.  
4.Analyze model effectiveness and behavior. 
5. Finding the best value of 'K' for this dataset using K-Tuning.
6. Ploting a line graph to see proper K tuning and decide the best value of K for dataset.

 # Dataset
The project uses two datasets:

- **train_human_predict.csv** → Used for training the model  
- **test_human_predict.csv** → Used for testing and evaluation  

These datasets contain:
- Input features describing individuals  
- A target variable representing the outcome to be predicted  

*These datasets are used to train and test a machine learning model for predicting human-related outcomes or behavior based on given features.*

# Data Preprocessing
1. Loaded datasets using Pandas.
2. Checked for missing values in columns.
3. Separated features (X) and target (y).
4. Applied scaling using **StandardScaler**.
5. Split training data using **train_test_split**  
6. Modelling the dataset using KNN.

 # K-Nearest Neighbors (KNN)
- Used for classification.  
- Predicts based on similarity (distance between data points).  

**Why KNN?**
- Simple and intuitive.  
- Works well for structured datasets.  
- Effective for pattern-based classification.

# Evaluation Metrics

The model is evaluated using:

1. **Accuracy** → Overall correctness  
2. **Precision** → Correct positive predictions  
3. **Recall** → Ability to detect actual positives  
4. **Confusion Matrix** → Detailed prediction results  

# Observations
1. KNN performed well for classification tasks.  
2. Precision and Recall helped evaluate performance beyond accuracy.  
3. Model performance depends on value of K (number of neighbors).  
4. Scaling improved model accuracy significantly.

---

# Analysis
1. Feature scaling was crucial for KNN since it relies on distance  
2. Choosing the right value of K impacts model performance  
3. Precision and Recall provide better insight for classification problems  
4. KNN works well for smaller datasets but may become slow for large datasets  
5. Proper preprocessing improves model reliability  

# Libraries Used
- Pandas  
- Matplotlib 
- Scikit-learn:
  - StandardScaler  
  - train_test_split  
  - KNeighborsClassifier  
  - Metrics:
    - accuracy_score  
    - precision_score  
    - recall_score   
    - confusion_matrix  

# Project Structure
Human_Prediction_Project/
│
├── train_human_predict.csv  
├── test_human_predict.csv  
├── KNN_Precision_Recall.ipynb  
├── README.md  

# Key Takeaway
This project demonstrates how KNN and evaluation metrics like precision and recall can be used to effectively predict human behavior and analyze model performance.
