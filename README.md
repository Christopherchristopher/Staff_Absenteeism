# Staff_Absenteeism
This an Explanatory Data Analysis and a Predictive Machine Learning model  building for absenteeism in the workplace
The business environment is becoming more competitive than it use to be which leads to increase pressure in the workplace.It is then reasonable to say that unacheiveable business goals and the elevated risk of unemployemnent can lead to increase stress levels which affects the employee and his attitude towrard work,This might result to minor ilness which might make the employee be absent from work. We want to develop a  machine learning model that predicts employee abseenteeism from work.

It consists of the Exploratory Data Analysis and subsequently, machine learning modeling of employee abseenteeism .
I started out by importing our dataset into my Jupyter notebook, and printing out the first five and last five roles just to have an overview of the kind of data I will working with.


## Exploratory Data Analysis
1.Understand the variables in the dataset: Having an overview understanding of the data by printing the shape, the column values, and the data types of the dataset.
2.Cleaning the Data: Checking for incomplete dataset and dropping columns where neccessary
3.Analyse relationships between variables
4Explore and visualize relationships:

### Model Building
Importing the relevant libraries and classifiers
1.	Model Selection : Our  problem is a classification problem and so therefore we have decided to go with any of the classification algorithms.: DecisionTreeClassifier
2.	 Split : Understating our predictors(x) and targets(y) and splitting our dataset accordingly
3.	LogisticRegression: We fit and train our model using this algorithm
