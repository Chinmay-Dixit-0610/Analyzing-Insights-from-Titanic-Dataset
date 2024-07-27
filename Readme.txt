
Titanic Dataset: Exploratory Data Analysis and Data Cleaning

Overview
This project involves performing Exploratory Data Analysis (EDA) and data cleaning on the Titanic dataset. The aim is to gain insights into the data, understand the key features, and prepare the data for further analysis or modeling.

Project Structure

Data: The dataset is sourced from the Kaggle Titanic dataset.
EDA: Visualizations and statistical analysis to understand the distribution of features and identify patterns.
Data Cleaning: Steps to handle missing values, outliers, and categorical variables, ensuring the dataset is ready for modeling.
Features Explored
Survival: Whether each passenger survived (0 = No, 1 = Yes).
Pclass: Passenger's class (1st, 2nd, 3rd).
Name: Passenger's name, used for extracting titles.
Sex: Passenger's gender.
Age: Passenger's age, with missing values filled based on median values by groups.
SibSp: Number of siblings or spouses aboard.
Parch: Number of parents or children aboard.
Ticket: Ticket number, analyzed for any patterns.
Fare: Fare paid by the passenger.
Cabin: Cabin number, analyzed for its significance despite many missing values.
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Installation
To run this project, you need Python 3.x and the following libraries:

pandas
numpy
matplotlib
seaborn
missingno
You can install these dependencies using pip:

bash
Copy code
pip install pandas numpy matplotlib seaborn missingno
Usage
Clone or Download the Repository:
Clone the repository using Git:
bash
Copy code
git clone https://github.com/Chinmay-Dixit-0610/Titanic-EDA-Data-Cleaning.git
Or download the ZIP file directly from GitHub and extract the contents.
Run the Jupyter Notebook:
Navigate to the project directory and open the Jupyter Notebook titanic_eda_data_cleaning.ipynb.
Follow the steps in the notebook to load data, perform EDA, and clean the dataset.
Exploratory Data Analysis (EDA)
Data Visualization: Used to understand the distribution and relationship of features.
Bar plots, histograms, and box plots for categorical and numerical features.
Heatmaps and pair plots for correlation analysis.
Feature Engineering: Extracted new features such as family size, title from names, and fare per person.
Data Cleaning Steps
Handling Missing Values:
Imputation of missing ages using the median of similar groups.
Filling missing embarked data with the most common port.
Dropping or categorizing missing cabin information.
Outlier Treatment: Identified and treated outliers in fare and age distributions.
Encoding Categorical Variables: Converted categorical features like 'Sex' and 'Embarked' into numerical format using one-hot encoding.
Results
The cleaned dataset is ready for further analysis or modeling. Key insights from the EDA include the significant impact of passenger class, gender, and family size on survival rates.

Contributing
Contributions are welcome! Feel free to fork the repository, make enhancements, and submit a pull request.


Acknowledgements
Thanks to the Kaggle Titanic Competition for providing the dataset.
Special thanks to the data science community for resources and inspiration.