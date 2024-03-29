# Kaggle Competitions 🏆
Repository for my Kaggle competitions.
## Titanic - Machine Learning from Disaster
### 1. Download the dataset
You can find the dataset on the [Kaggles page](https://www.kaggle.com/competitions/titanic/data).

### 2. EDA - Exploratory Data Analysis
In statistics, EDA is an approach of analyzing data sets to summarize their main characteristics, often using statistical graphics and other data visualization methods. Primarily EDA is for seeing what the data can tell us beyond the formal modeling and thereby contrasts traditional hypothesis testing.

#### Features:
  - PassengerId - Passenger ID - Number
  - Survived - Survived - Bool
  - Pclass - Ticket class - available 1 = 1st, 2 = 2nd, 3 = 3rd - Number
  - Name - First name, Last Name and optional Title - String
  - Sex - Sex of passenger - available: male and female - String
  - Age - Age in years - Number
  - SibSp - of siblings / spouses aboard the Titanic - Number
  - Parch - of parents / children aboard the Titanic - Number
  - Ticket - Ticket Id - String
  - Fare - Passenger fare / Ticker price - Number
  - Cabin - Cabin number - String
  - Embarked - Port of Embarkation - available C = Cherbourg, Q = Queenstown, S = Southampton - String

#### Data preparation
Merging train and test sets during cleaning data period.
We will separate them before training and evaluation.

#### Feature engineering
FE is the process of selecting, manipulating, and transforming raw data into features that can be used later in learning. <br>
_Example:_ <br>
If we have data about prices of properties in x city. It shows area of the house and total price. We can create new data column to display the cost per square meters.

### 3. Train and validation
Firstly we will compare simpler models and choose the best.
Secondly, we will create neural network in PyTorch to try and get best prediction.
