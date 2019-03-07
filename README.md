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
