# PA-3-ECE-2112
# CARREOS, Christian Benedict R.
Objectives:
1. Create a code that solve the given problems using the Pandas Library.
2. Identify the code and functions in the Pandas Library.
3. Test the formulated codes with the functions from the Pandas Library for the saved csv file

# Problem
1. PROBLEM 1:

a. Load the corresponding .csv file into a data frame named cars using pandas
b. Display the first five and last five rows of the resulting cars.

3. PROBLEM 2:

a. Display the first five rows with odd-numbered columns (columns 1, 3, 5, 7...) of cars.
b. Display the row that contains the ‘Model’ of ‘Mazda RX4’.
c. How many cylinders (‘cyl’) does the car model ‘Camaro Z28’ have?
d. Determine how many cylinders (‘cyl’) and what gear type (‘gear’) do the car models ‘Mazda RX4
Wag’, ‘Ford Pantera L’ and ‘Honda Civic’ have.


# Expected Outputs:
PROBLEM 1
1. The loaded cars.csv file with all the data.
2. The rows of the first five cars based on the loaded cars.csv file.
3. The rows of the last five cars based on the loaded cars.csv file.

Functions Used from the Pandas Library:
1. pd.read_csv() to load the dataset.
2. cars.head() to display the first five rows.
3. cars.tail() to display the last five rows.
   

PROBLEM 2:
1. It is expected to load the downloaded csv file.
2. The first five rows with odd-numbered columns (columns 1, 3, 5, 7...) of cars from the cars.csv file.
3. The row of 'Camaro Z28' with the cylinder column which shows the number of the cylinders.
4. The row of 'Mazda RX4 Wag', 'Ford Pantera L' and 'Honda Civic' with the cylinder column and gear type column which shows the cylinders and gear type of each car.

Functions and Operations Used from the Pandas LIbrary:
1. Slicing and subsetting using iloc and loc.
2. Filter Data using Logical indexing
3. Locating specific columns and rows.


