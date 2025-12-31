This project interprets data on the performance of students and trains machine learning models.
to determine math scores depending on demographic and academic characteristics including
reading score, writing score, parental education, and so on.

The notebook includes:
Preprocessing and loading of data.
Exploratory Data Analysis (EDA)
Feature encoding
Model training and assessment.
New student profile prediction.

Technologies/Libraries used.
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

Project Files
Untitled.ipynb - Analysis + models (main jupyter notebook).
Studentsperformance.csv - Data set of student performance.

Dataset Description
Some of the features included in the dataset are:
Gender
Race/ethnicity
Parental level of education
Lunch type
Test preparation course
Reading score
Writing score
Math score (target variable)

Exploratory Data Analysis
Checked for missing values
Where needed, applied forward fill.
Histograms of distribution of math scores.

[?][?] Data Preprocessing
One-hot encoded the categorical variables.
Divide data into 2 sets of data training and testing (80/20 split).

Types of Machine Learning Models.
Linear Regression
Decision Tree Regressor

Evaluation Metrics:
Mean Absolute Error (MAE)

Results
Relationships between academic features and math scores were learned successfully using models.
It was used to create predictions of unknown test data.
Predicted math marks were made using a custom student profile.

Example Prediction
The scores of a new student in the area of reading and writing were given, and the trained model.
made predictions of the math score to be expected by the patterns learned.

>[?] How to Run the Notebook
Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn.
