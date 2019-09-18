# Springboard_Mini-Projects
**Contains Mini Projects for the Springboard Bootcamp**

[JSON examples and exercise](https://nbviewer.jupyter.org/github/pmleffers/Springboard_Mini-Projects/blob/a8cb32532d66391dfedabcbcff83200321757003/sliderule_dsi_json_exercise.ipynb)
+ get familiar with packages for dealing with JSON
+ study examples with JSON strings and files 
  1. Find the 10 countries with most projects
  2. Find the top 10 major project themes (using column 'mjtheme_namecode')
  3. In 2. above you will notice that some entries have only the code and the name is missing. Create a dataframe with the missing names filled in.

[SQL Mini-Project](https://nbviewer.jupyter.org/github/pmleffers/Springboard_Mini-Projects/blob/090c72a8e7da9f2034039764605023da0bad953e/Sql_Springboard.ipynb)
+ Work with SQL-based databases
+ Learn and write basic SQL queries up to basic aggregations and joins
+ Criteria:
  1. The code runs successfully.
  2. The submission shows that the correct solutions to all of the 10
problems have been produced.
  3. The submission demonstrates an understanding of the various
types of joins, aggregations, filters, and subqueries.
  4. The project is delivered as a .sql file (as stated in the
instructions), and uploaded to GitHub.

+ Questions:
  1. Some of the facilities charge a fee to members, but some do not.
Please list the names of the facilities that do.
  2. How many facilities do not charge a fee to members? 
  3. How can you produce a list of facilities that charge a fee to members,
where the fee is less than 20% of the facility's monthly maintenance cost?
Return the facid, facility name, member cost, and monthly maintenance of the
facilities in question.
  4. How can you retrieve the details of facilities with ID 1 and 5?
Write the query without using the OR operator.
  5. How can you produce a list of facilities, with each labelled as
'cheap' or 'expensive', depending on if their monthly maintenance cost is
more than $100? Return the name and monthly maintenance of the facilities
in question.
  6. You'd like to get the first and last name of the last member(s)
who signed up. Do not use the LIMIT clause for your solution.
  7. How can you produce a list of all members who have used a tennis court?
Include in your output the name of the court, and the name of the member
formatted as a single column. Ensure no duplicate data, and order by
the member name.
  8. How can you produce a list of bookings on the day of 2012-09-14 which
will cost the member (or guest) more than $30? Remember that guests have
different costs to members (the listed costs are per half-hour 'slot'), and
the guest user's ID is always 0. Include in your output the name of the
facility, the name of the member formatted as a single column, and the cost.
Order by descending cost, and do not use any subqueries.
  9. This time, produce the same result as in Q8, but using a subquery. 
  10. Produce a list of facilities with a total revenue less than 1000.
The output of facility name and total revenue, sorted by revenue. Remember
that there's a different cost for guests and members!

[API Mini-Project](https://nbviewer.jupyter.org/github/pmleffers/Springboard_Mini-Projects/blob/master/api_data_wrangling_mini_project.ipynb)

Practice new data wrangling techniques. 
+ The code runs successfully.
+ The submission shows that the correct solutions to the 6 mandatory problems are produced.
+ The code in the submission is well commented
+ The submission demonstrates understanding of each part of the solution.
+ The project doesn't contain any unnecessary printouts.
  1. Collect data from the Franfurt Stock Exchange, for the ticker AFX_X, for the whole year 2017 (keep in mind that the date format is YYYY-MM-DD).
  2. Convert the returned JSON object into a Python dictionary.
  3. Calculate what the highest and lowest opening prices were for the stock in this period.
  4. What was the largest change in any one day (based on High and Low price)?
  5. What was the largest change between any two days (based on Closing Price)?
  6. What was the average daily trading volume during this year? 
  7. (Optional) What was the median trading volume during this year. (Note: you may need to implement your own function for calculating the median.)
  
[Sliderule DSI Inferential Statistics Exercise 1](https://nbviewer.jupyter.org/github/pmleffers/Springboard_Mini-Projects/blob/a5b03f6943f8e6c0d25edb67f5cf695675db2091/sliderule_dsi_inferential_statistics_exercise_1.ipynb)

The mean normal body temperature was held to be 37∘C or 98.6∘F for more than 120 years since it was first conceptualized and reported by Carl Wunderlich in a famous 1868 book. But, is this value statistically correct?
+ Answer the following questions in this notebook below and submit to your Github account.

- Is the distribution of body temperatures normal?
  1. Although this is not a requirement for the Central Limit Theorem to hold (read the introduction on Wikipedia's page about the CLT carefully: https://en.wikipedia.org/wiki/Central_limit_theorem), it gives us some peace of mind that the population may also be normally distributed if we assume that this sample is representative of the population.
  2. Think about the way you're going to check for the normality of the distribution. Graphical methods are usually used first, but there are also other ways: https://en.wikipedia.org/wiki/Normality_test 
- Is the sample size large? Are the observations independent? 
  1. Remember that this is a condition for the Central Limit Theorem, and hence the statistical tests we are using, to apply. 
- Is the true population mean really 98.6 degrees F? 
  1. First, try a bootstrap hypothesis test.
  2. Now, let's try frequentist statistical testing. Would you use a one-sample or two-sample test? Why?
  3. In this situation, is it appropriate to use the t or z statistic?
  4. Now try using the other test. How is the result be different? Why? 
- Draw a small sample of size 10 from the data and repeat both frequentist tests.
  1. Which one is the correct one to use?
  2. What do you notice? What does this tell you about the difference in application of the t and z statistic? 
- At what temperature should we consider someone's temperature to be "abnormal"?
  1. As in the previous example, try calculating everything using the boostrap approach, as well as the frequentist approach.
  2. Start by computing the margin of error and confidence interval. When calculating the confidence interval, keep in mind that you should use the appropriate formula for one draw, and not N draws

- Is there a significant difference between males and females in normal temperature?
  1. What testing approach did you use and why?
  2. Write a story with your conclusion in the context of the original problem. 
  
[Sliderule DSI Inferential Statistics Exercise 2](https://nbviewer.jupyter.org/github/pmleffers/Springboard_Mini-Projects/blob/b8343f658307e78f70e9062987a60337dbefb0e6/sliderule_dsi_inferential_statistics_exercise_2.ipynb)

You will perform a statistical analysis to establish whether race has a significant impact on the rate of callbacks for resumes.
1. What test is appropriate for this problem? Does CLT apply?
2. What are the null and alternate hypotheses?
3. Compute margin of error, confidence interval, and p-value. Try using both the bootstrapping and the frequentist statistical approaches.
4. Write a story describing the statistical significance in the context or the original problem.
5. Does your analysis mean that race/name is the most important factor in callback success? Why or why not? If not, how would you amend your analysis?

[sliderule_dsi_inferential_statistics_exercise_3](https://nbviewer.jupyter.org/github/pmleffers/Springboard_Mini-Projects/blob/a28bc64b4e853a8cb751ae5455df68e36e40a993/sliderule_dsi_inferential_statistics_exercise_3.ipynb)

Hospital Readmissions Data Analysis and Recommendations for Reduction
Background

In October 2012, the US government's Center for Medicare and Medicaid Services (CMS) began reducing Medicare payments for Inpatient Prospective Payment System hospitals with excess readmissions. Excess readmissions are measured by a ratio, by dividing a hospital’s number of “predicted” 30-day readmissions for heart attack, heart failure, and pneumonia by the number that would be “expected,” based on an average hospital with similar patients. A ratio greater than 1 indicates excess readmissions.
Exercise Directions
+ In this exercise, you will:
1. critique a preliminary analysis of readmissions data and recommendations (provided below) for reducing the readmissions rate
    construct a statistically sound analysis and make recommendations of your own

[Mini_Project_Linear_Regression](https://nbviewer.jupyter.org/github/pmleffers/Springboard_Mini-Projects/blob/357884edcacde980e86b5a484f1f6861878ebf93/Mini_Project_Linear_Regression.ipynb)

This is a very quick run-through of some basic statistical concepts, adapted from Lab 4 in Harvard's CS109 course. Please feel free to try the original lab if you're feeling ambitious :-) The CS109 git repository also has the solutions if you're stuck.
+ Linear Regression Models
+ Prediction using linear regression

Linear regression is used to model and predict continuous outcomes with normal random errors. There are nearly an infinite number of different types of regression models and each regression model is typically defined by the distribution of the prediction errors (called "residuals") of the type of data. Logistic regression is used to model binary outcomes whereas Poisson regression is used to predict counts. In this exercise, we'll see some examples of linear regression as well as Train-test splits.

The packages we'll cover are: statsmodels, seaborn, and scikit-learn. While we don't explicitly teach statsmodels and seaborn in the Springboard workshop, those are great libraries to know.

[Mini_Project_Logistic_Regression](https://nbviewer.jupyter.org/github/pmleffers/Springboard_Mini-Projects/blob/bd8e85a229de1fec389b7196c63b4bcb2733fbeb/Mini_Project_Logistic_Regression.ipynb)

We turn our attention to classification. Classification tries to predict, which of a small set of classes, an observation belongs to. Mathematically, the aim is to find y, a label based on knowing a feature vector x. For instance, consider predicting gender from seeing a person's face, something we do fairly well as humans. To have a machine do this well, we would typically feed the machine a bunch of images of people which have been labelled "male" or "female" (the training set), and have it learn the gender of the person in the image from the labels and the features used to determine gender. Then, given a new photo, the trained algorithm returns us the gender of the person in the photo.

There are different ways of making classifications. One idea is shown schematically in the image below, where we find a line that divides "things" of two different types in a 2-dimensional feature space. The classification show in the figure below is an example of a maximum-margin classifier where construct a decision boundary that is far as possible away from both classes of points. The fact that a line can be drawn to separate the two classes makes the problem linearly separable. Support Vector Machines (SVM) are an example of a maximum-margin classifier.

[Mini_Project_Naive_Bayes](https://nbviewer.jupyter.org/github/pmleffers/Springboard_Mini-Projects/blob/e91c3b79fda481370dd5d9d57796a1959089a09a/Mini_Project_Naive_Bayes.ipynb)

In the mini-project, you'll learn the basics of text analysis using a subset of movie reviews from the rotten tomatoes database. You'll also use a fundamental technique in Bayesian inference, called Naive Bayes. This mini-project is based on [Lab 10 of Harvard's CS109](https://github.com/cs109/2015lab10) class.  Please free to go to the original lab for additional exercises and solutions.

[Mini_Project_Clustering](https://nbviewer.jupyter.org/github/pmleffers/Springboard_Mini-Projects/blob/1dbb3886a36425a42ac009cf8049075462f0971b/Mini_Project_Clustering.ipynb)

This mini-project is based on [this blog post](http://blog.yhat.com/posts/customer-segmentation-using-python.html) by yhat. Please feel free to refer to the post for additional information, and solutions.

[Mini_Project_Tree-Based_Algorithms](https://nbviewer.jupyter.org/github/pmleffers/Springboard_Mini-Projects/blob/ff6efba67cc32901fd91f026eff1cccf4a82857a/Mini_Project_Tree-Based_Algorithms.ipynb)

Building Your First Decision Tree Model

So, now it's time to jump straight into the heart of the matter. Your first task, is to build a Decision Tree model, using the aforementioned "German Credit" dataset, which contains 1,000 records, and 62 columns (one of them presents the labels, and the other 61 present the potential features for the model.)

For this task, you will be using the scikit-learn library, which comes already pre-installed with the Anaconda Python distribution. In case you're not using that, you can easily install it using pip.

Before embarking on creating your first model, we would strongly encourage you to read the short tutorial for Decision Trees in scikit-learn (http://scikit-learn.org/stable/modules/tree.html), and then dive a bit deeper into the documentation of the algorithm itself (http://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html).

Also, since you want to be able to present the results of your model, we suggest you take a look at the tutorial for accuracy metrics for classification models (http://scikit-learn.org/stable/modules/model_evaluation.html#classification-report) as well as the more detailed documentation (http://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html).

Finally, an amazing resource that explains the various classification model accuracy metrics, as well as the relationships between them, can be found on Wikipedia: https://en.wikipedia.org/wiki/Confusion_matrix


[Spark Mini-Project: Databricks edition](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/8473886147007670/1141464256888140/5089459760228433/latest.html)

In this exercise we will play with Spark Datasets & Dataframes, some Spark SQL, and build a couple of binary classifiaction models using Spark ML (with some MLlib too).

The set up and approach will not be too dissimilar to the standard type of approach you might do in Sklearn. Spark has matured to the stage now where for 90% of what you need to do (when analysing tabular data) should be possible with Spark dataframes, SQL, and ML libraries. This is where this exercise is mainly trying to focus.

Feel free to adapt this exercise to play with other datasets readily availabe in the Databricks enviornment (they are listed in a cell below).
Getting Started

To get started you will need to create and attach a databricks spark cluster to this notebook. This notebook was developed on a cluster created with:

    Databricks Runtime Version 4.0 (includes Apache Spark 2.3.0, Scala 2.11)
    Python Version 3

[Data Analysis Interview Challenge](https://nbviewer.jupyter.org/github/pmleffers/Springboard_Mini-Projects/blob/master/Data%20Analysis%20Interview%20Challenge.ipynb)
This is your chance to wow us with creative and rigorous solutions! Please include your code at
the end of your submission, or in a separate file. We also accept incomplete solutions.
Part 1 ‑ Exploratory data analysis
The attached logins.json file contains (simulated) timestamps of user logins in a particular
geographic location. Aggregate these login counts based on 15minute
time intervals, and
visualize and describe the resulting time series of login counts in ways that best characterize the
underlying patterns of the demand. Please report/illustrate important features of the demand,
such as daily cycles. If there are data quality issues, please report them.
Part 2 ‑ Experiment and metrics design
The neighboring cities of Gotham and Metropolis have complementary circadian rhythms: on
weekdays, Ultimate Gotham is most active at night, and Ultimate Metropolis is most active
during the day. On weekends, there is reasonable activity in both cities.
However, a toll bridge, with a two way
toll, between the two cities causes driver partners to tend
to be exclusive to each city. The Ultimate managers of city operations for the two cities have
proposed an experiment to encourage driver partners to be available in both cities, by
reimbursing all toll costs.
1. What would you choose as the key measure of success of this experiment in
encouraging driver partners to serve both cities, and why would you choose this metric?
2. Describe a practical experiment you would design to compare the effectiveness of the
proposed change in relation to the key measure of success. Please provide details on:
a. how you will implement the experiment
b. what statistical test(s) you will conduct to verify the significance of the
observation
c. how you would interpret the results and provide recommendations to the city
operations team along with any caveats.
Part 3 ‑ Predictive modeling
Ultimate is interested in predicting rider retention. To help explore this question, we have
provided a sample dataset of a cohort of users who signed up for an Ultimate account in
January 2014. The data was pulled several months later; we consider a user retained if they
were “active” (i.e. took a trip) in the preceding 30 days.
We would like you to use this data set to help understand what factors are the best predictors
for retention, and offer suggestions to operationalize those insights to help Ultimate.
The data is in the attached file ultimate_data_challenge.json. See below for a detailed
description of the dataset. Please include any code you wrote for the analysis and delete the
dataset when you have finished with the challenge.
1. Perform any cleaning, exploratory analysis, and/or visualizations to use the provided
data for this analysis (a few sentences/plots describing your approach will suffice). What
fraction of the observed users were retained?
2. Build a predictive model to help Ultimate determine whether or not a user will be active
in their 6th month on the system. Discuss why you chose your approach, what
alternatives you considered, and any concerns you have. How valid is your model?
Include any key indicators of model performance.
3. Briefly discuss how Ultimate might leverage the insights gained from the model to
improve its longterm
rider retention (again, a few sentences will suffice).
Data description
● city: city this user signed up in
● phone: primary device for this user
● signup_date: date of account registration; in the form ‘YYYY MM DD’
● last_trip_date: the last time this user completed a trip; in the form ‘YYYY MM DD’
● avg_dist: the average distance in miles per trip taken in the first 30 days after signup
● avg_rating_by_driver: the rider’s average rating over all of their trips
● avg_rating_of_driver: the rider’s average rating of their drivers over all of their trips
● surge_pct: the percent of trips taken with surge multiplier > 1
● avg_surge: The average surge multiplier over all of this user’s trips
● trips_in_first_30_days: the number of trips this user took in the first 30 days after
signing up
● ultimate_black_user: TRUE if the user took an Ultimate Black in their first 30 days;
FALSE otherwise
● weekday_pct: the percent of the user’s trips occurring during a weekday
