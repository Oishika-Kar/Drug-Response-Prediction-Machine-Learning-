**Drug Response Prediction Mini Project**

**Objective:**
The goal of this mini project is to explore the Decision Trees machine learning algorithm for predicting drug responses in healthcare contexts. By building a model from past patient data and associated medication responses, the aim is to predict the classification of an unknown patient or suggest the most suitable drug for a new patient. The dataset includes information on patients' age, sex, blood pressure, cholesterol levels, and the drug they responded to (Drug A, Drug B, Drug C, Drug X, and Drug Y).

**Table of Contents:**
1. **About the Dataset:**
   - Description of the dataset, including the premise of the medical research and the significance of the data in guiding personalized treatment strategies.

2. **Downloading the Data:**
   - Using the Pandas library to read the data directly into a dataframe from IBM Object Storage.

3. **Pre-processing:**
   - Declaring variables for the feature matrix (X) and response vector (y).
   - Excluding the column containing the target name since it doesn't contain numeric values.
   - Converting categorical features to numeric using LabelEncoder.

4. **Setting up the Decision Tree:**
   - Using train/test split on the decision tree.
   - Converting categorical features to dummy/indicator variables.
   - Using the DecisionTreeClassifier with criterion='entropy' and fitting the data with training sets.

5. **Modeling:**
   - Creating an instance of DecisionTreeClassifier with entropy as the criterion and a specified max depth.
   - Fitting the model with the training feature matrix and response vector.

6. **Prediction:**
   - Splitting the data into training and testing sets.
   - Making predictions using the trained Decision Tree model.

7. **Evaluation:**
   - Checking the accuracy of the model using the accuracy score.

8. **Visualization:**
   - Visualizing the Decision Tree using Graphviz and displaying it as an image.

**How to Use:**
- Clone the repository.
- Ensure the required libraries are installed (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `pydotplus`, `python-graphviz`).
- Run the Jupyter notebook step by step to understand the process.
- Explore the Decision Tree model, predictions, and accuracy.
- View the visual representation of the Decision Tree.

**Note:**
- This project serves as an educational exercise in applying Decision Trees to healthcare data.
- Additional improvements and optimizations can be explored for enhancing the model's performance.
- Ensure you have the necessary permissions to access the provided dataset.
