#Calculate Daily Sales Projections
Part One:

1. Stores the min/max hourly customers, and the average cookies per customer, in object properties
2. Uses a method of that object to generate a random number of customers per hour.
3. Calculate simulated amounts of cookies purchased for each hour using average cookies purchased and  the random number of customers generated
4. Store the results for each location in a separate array
5. Display the values of each array as unordered lists in the browser
6. Calculating the sum of these hourly totals; your output for each location should look like this:

    Pike Place Market
    - 10am: 56 cookies
    - 11am: 77 cookies
    - 12pm: 93 cookies
    - 1pm: 144 cookies
    - 2pm: 119 cookies
    - 3pm: 84 cookies
    - 4pm: 61 cookies
    - 5pm: 23 cookies
    - Total: 657 cookies
    
Display the lists on index.html.

Here are the starting numbers that you'll need to build these objects:

Location        | Min / Cust | Max / Cust | Avg Cookie / Sale
----------------|------------|------------|-------------------
Pike Place      |      17    |     88     |        5.2
SeaTac Airport  |      6     |     24     |        1.2
Southcenter     |      11    |     38     |        1.9
Bellevue Square |      20    |     48     |        3.3
Alki            |      3     |     24     |        2.6
