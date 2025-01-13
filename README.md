 
---

# **Titanic Data Analysis with Python**

This project involves analyzing the Titanic dataset to extract meaningful insights. It includes data cleaning, transformation, and visualization. The goal is to showcase Python's data manipulation capabilities using libraries like **Pandas**, **NumPy**, and **Matplotlib**.

---

 
 

## **Project Overview**
The Titanic dataset is one of the most well-known datasets for data analysis. This project demonstrates:
- Data cleaning (handling missing values, renaming categories).
- Data visualization (histograms, boxplots).
- Feature engineering (categorical conversions, creating new variables).

---

## **Dataset Description**
The dataset is a CSV file containing information about Titanic passengers:
- **Survived**: 0 = Died, 1 = Survived.
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- **Name**: Passenger's name.
- **Sex**: Gender.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Ticket**: Ticket number.
- **Fare**: Passenger fare.
- **Cabin**: Cabin number.
- **Embarked**: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

---

## **Project Workflow**
1. **Data Loading**:
   Load the dataset using Pandas:
   
2. **Data Cleaning**:
   - Dropped irrelevant columns like `PassengerId` and `Ticket`.
   - Filled missing values in the `Age` column with the median.
   - Simplified the `Cabin` column to retain only the first letter of the cabin code.

3. **Feature Engineering**:
   - Converted the `Survived` column to categorical labels: "Died" and "Survived".
   - Renamed `Pclass` categories to "Class1", "Class2", "Class3".

4. **Visualization**:
   - Analyzed age distribution:
    
   - Created a boxplot for fare distribution:
     
---

## **Features**
- **Data Cleaning**: Handle missing values and simplify columns.
- **Data Transformation**: Convert numerical and categorical variables.
- **Visualization**: Insights into age, fare distribution, and survival trends.

---

  
 
