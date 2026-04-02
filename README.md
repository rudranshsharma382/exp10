# exp10

#NAME-Rudransh Sharma 

#PRN-25070123096

Aim

To demonstrate fundamental data manipulation and analysis operations using the Python Pandas library, including data structure creation, inspection, updating, and basic statistical analysis.

Theory

Pandas is a high-performance, open-source Python library used for structured data analysis and cleaning. It primarily utilizes two data structures:

Series: A one-dimensional labeled array capable of holding any data type.

DataFrame: A two-dimensional, size-mutable, and potentially heterogeneous tabular data structure with labeled axes (rows and columns).
Key functions demonstrated in the code include:

1. Inspection: head(), tail(), shape, ndim, and dtypes.

2. Selection: .loc (label-based) and .iloc (integer-based indexing).

3. Transformation: Adding new columns, updating values, and dropping data using .drop().

4. Analysis: Aggregation functions like mean(), max(), and min(), along with boolean filtering.

Algorithm

1. Importing: Load the pandas library with the alias pd.

2. Creation: * Initialize a Series using a list of integers.

3. Initialize a DataFrame using a dictionary of lists (Names and Marks).

4. Inspection:

5. Check metadata using shape (rows/cols), ndim (dimensions), and size (total elements).

6. Display headers and column names.


Manipulation:

1. Access specific columns by name and rows by index.

2. Append a new "Grade" column based on specific criteria.

3. Modify existing data (e.g., updating a student's marks) using .loc or .iloc.

4. Remove unwanted columns using the drop() method with inplace=True.

5. Statistical Calculation: Compute the average, maximum, and minimum values of the "Marks" column.

6. Filtering: Apply a conditional mask to display only rows where "Marks" exceed a specific threshold (e.g., > 80).


Conclusion

We have successfully implemented the core functionalities of the Pandas library. Through this experiment, we observed how DataFrames facilitate efficient tabular data handling, allowing for easy data cleaning, selective updates, and rapid statistical computation, which are essential steps in the Exploratory Data Analysis (EDA) process.
