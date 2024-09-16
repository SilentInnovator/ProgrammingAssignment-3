# ProgrammingAssignment-3
Problem 1:
- Load cars.csv into Jupyter notebook via Panda

- Used head() and tail() commands to get the first and last 5 rows of the table.


Problem 2:
- Load cars.csv into Jupyter notebook via Panda

- Used the cars.loc [[0,1,2,3,4], ['Model', 'cyl', 'hp', 'wt', 'vs', 'gear']] command to have the program display the first 5 rows with odd numbered columns. I typed the inputs manually as I did not find a better code to make the program produce odd numbered columns automatically.

- Used the cars.iloc [0] command to display the first row of the table which contains the Mazda RX4.

- Used the cars.loc [[23],['cyl']] code to display the number of cylinders of a Camaro Z28.

- Used the cars.loc [[1, 18, 28],['cyl', 'gear']] code to show the number of cylinders and gear type of the Mazda RX4 Wag, Ford Pantera L, and Honda Civic specifically.
