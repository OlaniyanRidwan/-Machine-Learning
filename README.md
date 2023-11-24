# -Machine-Learning
Topic: Titanic- Machine Learning Predictions. 
Titanic as we all know happened in 1912, a shipwreck which caused the death of a lot of passengers onboard. 
With a recorded data on all these passengers
the task was aimed at predicting people who survived and those who didn't using the data gotten. 

Since it's outcome is binary in nature (survived or doesn't survive), we are expected to use the principle of Logistics Regression. 
However, checking each features in the dataset, we found out that some are categorical in nature like Ticket Class, Sex and Embarked features which goes against the usage of Logistics Regression which states that the features should be continuous in nature.
Nonetheless, keeping all options opened, we used both Logistics Regression and Decisions Tree Algorithm to model the preprocessed data(cleaned data) for the purpose of comparing the one with the best model score and accuracy score (from the metrics package). 
The model score of Decision Trees gave 92% score and 78% accuracy score while that of logistics regression gave 81% model score and 78% accuracy score as well🤗...
