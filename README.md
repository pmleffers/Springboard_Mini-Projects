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

In this exercise, you will:

    critique a preliminary analysis of readmissions data and recommendations (provided below) for reducing the readmissions rate
    construct a statistically sound analysis and make recommendations of your own
