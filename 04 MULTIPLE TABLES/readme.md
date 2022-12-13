# Lyft Trip Data
### from CODECADEMY's *Learn SQL* course

Let’s practice what we learned about joins by combining rows from different tables.

Suppose you are a Data Analyst at Lyft, a ride-sharing platform. For a project, you were given three tables:

- trips: trips information
- riders: user data
- cars: autonomous cars

### Tasks (numbers are matched in the code)

1. Let’s examine the three tables. What are the column names?
2. What’s the primary key of *trips*? What’s the primary key of *riders*? What’s the primary key of *cars*?
3. Try out a simple cross join between *riders* and *cars*. Is the result useful?
4. Suppose we want to create a Trip Log with the trips and its users. Find the columns to join between *trips* and *riders* and combine the two tables using a LEFT JOIN. Let *trips* be the left table.
5. Suppose we want to create a link between the *trips* and the *cars* used during those trips. Find the columns to join on and combine the *trips* and *cars* table using an INNER JOIN.
6. The new riders data are in! There are three new users this month. Stack the *riders* table on top of the new table named *riders2*.
7. What is the average *cost* for a trip?
8. Lyft is looking to do an email campaign for all the irregular users. Find all the *riders* who have used Lyft less than 500 times!
9. Calculate the number of cars that are *active*.
10. It’s safety recall time for cars that have been on the road for a while. Write a query that finds the two cars that have the highest *trips_completed*.
