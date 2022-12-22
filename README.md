# Topic: A Hybrid Technique For Credit Card Fraud Detection In Nigerian Banking System.

**Table of Content**

    1. Business Understanding.
    2. Data Understanding.
    3. Data Preparation.
    4. Model Development.
    5. Model Evaluation and Performance.
    6. Reference.

# Business Understanding
**Problem Definition:**
Every day, large sums of money are lost as a result of credit card fraud (Le Borgne, Siblini, Lebichot and Bontempi, 2022). 
Credit card fraud detection is a problem that requires the analysis of massive amounts of data in order to detect fraudulent patterns. 
The large volume of data, combined with the evolving techniques of hackers, makes it impossible for human investigators to deal with
the problem efficiently. Machine learning is being used to improve credit card fraud detection over the last ten years
(Le Borgne, Siblini, Lebichot and Bontempi, 2022). 

**Scope**

    1. Develop a (hybrid) model using Artificial Neural Networks and Genetic Algorithm for detecting credit card fraud.
    2. Run the developed model through a simulation. This will be accomplished by training the model developed to detect fraud patterns using the simulated dataset.
    3. Analyse the model developed using performance metrics of accuracy and speed of fraud detection. 
    4. Compare the model with the individual models that make up the hybrid.

**Plan**



# Data Acquisition and Understanding
**Raw Data**

The dataset used for this research work is obtained from a github repository:
https://github.com/Fraud-Detection-Handbook/fraud-detection-handbook, it was created by
(Patrick Chong and Yann-Ael Le Borgne, 2021). The dataset is a simulated credit card 
transaction containing of legitimate and fraudulent transactions. 
This dataset has about 6 features such as “Amount”, “Transaction ID”, “Customer ID”, “Fraud”, and so on, 
it's comprising only one data types numeric which includes both float and integer data type. 
The datasets is available at “https://github.com/Fraud-Detection-Handbook/fraud-detection-handbook”.  

**Below is the brief description of features in the dataset used during this project research.**

    1. The transaction ID: A transaction's unique identifier.
    2. The date and time: The transaction's date and time of occurrence.
    3. The customer ID: Each customer is identified by a unique number.
    4. The terminal ID: The merchant's unique identifier (or more precisely the terminal). Each terminal has a unique identifier.
    5. The transaction amount: The transaction's monetary value.
    6. The fraud label: A binary variable that has a value for both  legitimate and fraudulent transaction i.e (0 or 1).

# Data Preprocessing 
The approach for data pre-processing will include feature engineering, handling missing values,
correcting and data imbalances. The use of Python tools for data manipulation and visualization such as 
“Pandas”, “Matplotlib”, “Seaborn”, and “Numpy” where been used to achieve 
these preprocessing responsibilities. Pandas is a data manipulation tool 
that is used in cleaning, treating and filtering messy dataset, it’s an 
open source python library used by data scientist and data analyst for preparing 
data. Matplotlib and Seaborn are both python open source library used for visualizing data, 
they are used to creating different type of chart such as bar plot, line plot, 
box plot and so on, while Numpy which stands for Numerical Python is a python library 
used for working with arrays and numbers. Synthetic Minority Oversampling Technique (SMOTE) which is a statistical technique
for increasing the number of cases in your dataset in a balanced way.

# Model Development
The adoption of “Tensorflow Keras” which is a free and open source software library
for machine learning and artificial intelligence developed and maintained by Google. 
This framework was used during this research work. It is a widely accepted framework 
that is being used by researchers, students and developers, which makes it easier to 
build and deploy machine learning models

# Model Evaluation
Evaluating the performance of the machine learning algorithms is an essential 
part of any research work. This will show how each of the algorithms performed 
and to know which gives satisfactory or unsatisfactory results. We often use accuracy 
to weigh the model performance in classification algorithms, although it is not the only 
true way to judge the model. In this study, evaluation metrics like Accuracy, F1-Score, 
Confusion matrix, and Classification Report.


**Please see below on instruction on how to run the program:**


Step 1: First create a virtual environment name venv or any-name you most have python install in system. run =>

    python -m venv venv

Step 2: Activate the virtual environment

    venv/Scripts/activate

Step 3: Clone the repository

    mkdir Project
    cd Project

    git clone https://github.com/SilasEmma/FraudProject.git

Step 4: Install Python libraries

    pip install -r requirements.txt

Step 5: Run Jupyter notebook

    jupyter notebook

# Reference
* Patrick Chong and Yann-Ael Le Borgne, (2021). Fraud Detection Handbook.
               https://github.com/Fraud-Detection-Handbook/fraud-detection-handbook
