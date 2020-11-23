Matthew Thompson and Lowell Deschenes
11/15/20

# Week #4 Check In

## 1a)  Major activities/milestones planned for this week (in the timeline that you had going into the start of the week).

* Completed basic feature engineering
* Completed basic model implementation


## 1b)  Major activities/milestones accomplished this week (note: this may or may not actually be what was stated in 1a -- that's okay, as long as you're making progress and learning!).

* Lowell completed preliminary model optimization
  * He implemented random search cross validation for each of the models to find the optimal hyperparameters. Fine tuning can still be done.
* Matthew completed preliminary feature engineering
  * He created a new feature for the next days avalanche danger so we can use it as what we wish to predict.
  * He also created new features of the last 3 days of weather and snow features for each day to hopefully improve the robustness of the model.
  * He dropped unneeded features and filled NULL values with calculated estimates using values from other features.
* The new accuracy scores for each of the models are (predicting next day avalanche danger, last check-in we were predicting current day avalanche danger)
  * Decision Trees: Accuracy = 56%
  * Random Forest: Accuracy = 61%
  * Extra Trees: Accuracy = 61%
  * Logistic Regression: Accuracy = 63%
  * SVM: Accuracy = 63%
  * K-Nearest Neighbors: Accuracy = 57%
  * Gradient Boosting Classifier: Accuracy = 60%


## 2a)  Open challenges and questions (including what -- if anything -- are the challenges that Ethan or I can help provide feedback or pointers on?)

* An obvious open challenge is our currently low accuracy scores, however, these will improve with feature engineering and model optimization.
* The next day avalanche danger for the last day in each season is inaccurate because the model thinks it is referring to the first day of the next season. Our current idea for a solution to this is just to drop the rows from the last day of each season, because the next day avalanche danger for the second to last days will be accurate.


## 2b)  Major changes to research plan (if any, based on what you've learned or accomplished thus far, and the unexpected challenges you've faced this week)

* Nothing major, but realized that we needed more time for feature engineering and model implementation in order to accomplish decent (hopefully >80%) accuracy, so we allowed ourselves this time for this upcoming week. We pushed data visualization off to the same week that we create the project presentation.


## 3) Revised week-by-week timeline (this can be copy and pasted exactly from what you previously had if there are no changes, but assuming you are doing some course corrections along the way, it's good to have a revised timeline to refer to!)

November 15 – Check-In #4:
* Completed basic feature engineering
* Completed basic model implementation

November 22 – Check-In #5:
* Completed optimized feature engineering (UPDATED)
* Completed optimized model implementation (UPDATED)
* Completed data and model analysis

November 29 - Project Due Date:
* Completed visualizing results (UPDATED)
* Completed presentation (UPDATED)
