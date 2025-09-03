

# Titanic Survival Prediction

This repository contains a Jupyter Notebook that uses machine learning to predict the survival of passengers on the Titanic. The dataset used is the Titanic passenger list, and the model is built using a Random Forest Classifier to predict survival based on various features such as age, sex, and fare.

## Requirements

The following Python libraries are required to run the notebook:

* pandas
* numpy
* matplotlib
* scikit-learn

To install the required libraries, you can use:

```bash
pip install -r requirements.txt
```

Alternatively, you can install them individually:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Dataset

The notebook uses the **Titanic Dataset** from Kaggle, which contains information about passengers onboard the Titanic, including their age, class, sex, and whether they survived the disaster.

The dataset is read from a CSV file named `Titanic-Dataset.csv`.

## Steps Covered in the Notebook

1. **Data Loading and Inspection**
   The notebook loads the Titanic dataset from a CSV file and checks for missing values. It also calculates basic statistics such as the mean and standard deviation of the `Age` column.

2. **Data Preprocessing**
   Missing values in the `Age` column are filled with the mean age. The `Sex` column is mapped to numerical values (`male = 0, female = 1`). After preprocessing, we check if there are any remaining missing values.

3. **Exploratory Data Analysis**
   The notebook includes a visualization of the survival rate by sex, showing the percentage of male and female passengers who survived.

4. **Feature Selection**
   The notebook selects key features (`Pclass`, `Sex`, `Age`, `Fare`) and splits the data into feature (`X`) and target (`y`) variables.

5. **Model Building and Evaluation**
   A Random Forest Classifier is used to build the model. The data is split into training and testing sets, and the model is trained on the training data. Afterward, the model's performance is evaluated using Precision and Recall metrics.

## How to Use

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/YOUR_USERNAME/Titanic-Survival-Prediction.git
   ```

2. Navigate to the repository directory:

   ```bash
   cd Titanic-Survival-Prediction
   ```

3. Open the notebook file in Jupyter:

   ```bash
   jupyter notebook titanic_survival_prediction.ipynb
   ```

4. Run the cells step-by-step to perform the analysis and predictions.


