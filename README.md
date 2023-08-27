Exploratory Data Analysis (EDA) is a method used by data scientists to analyze and investigate datasets and summarize their main characteristics, often employing data visualization methods. 
It can help to answer questions about the data, or check some assumptions. EDA is often the first step in data analysis.

Dataset: Cardio-Vascular Disease Dataset
This dataset contains data from patients who have been observed for cardiovascular diseases. 
The dataset includes various factors such as age, gender, systolic blood pressure, cholesterol, etc. 
It also includes information on whether the patient has heart disease.
Step 1: Importing Libraries
Step 2: Loading the Dataset
Step 3: Understanding the Dataset
        df.describe()  
        df.info()
By using these functions, we can understand the numerical and categorical distribution of data.

Step 4: Checking for missing values

        dataset.isnull().sum()

It is crucial to check if the dataset contains any null or missing values.

Step 5: Data Visualization

Visualization can provide a factual basis for messages that you as an analyst want to convey.

Histograms can be used to represent the distribution of the data.

A correlation matrix can be used to understand the relationship between variables.

Box plots are used to identify outliers in the data.

Pair plots will help to understand the pairwise relationship and distribution between parameters.

        sns.pairplot(dataset)
