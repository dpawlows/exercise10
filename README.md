# Exercise 10 

For this exercise, create a file called pandasDA.py and add the code
necessary to complete the exercises in that file.

Problem 1
---------
Creating and manipulating a data frame.

1. Create a data frame that contains all of the information shown in the table in the file [stellar.jpg](stellar.jpg). Then, use the methods or
attributes of the data frame object to complete the following activities (i.e. don't just hard code the answers).
2. Print the shape of the data frame.
3. Print the maximum distance observed.
4. Sort the data frame by Absolute Magnitude and print the sorted data frame.
5. Get a subset of the data frame that only contains distance and absolute magnitude, sorted by absolute magnitude. Save the result to a new variable.
6. Convert this new data frame to a numpy array using the `to_numpy()`
  method of the data frame. Save the result to a new variable. Then,
  use the numpy array to plot the absolute magnitude as a function of distance. Save the plot as magVsDistance.png.
  
 Warning: Remember data types are important! In this assignment, it is really easy to create a dataframe that has data with the wrong data type. Make sure that once you create the dataframe, each column of data has the type that you expect. Please note that if you populate a numpy array with all of your data, that array can only hold data of a single type (unlike a python list which allows mixed types). This can lead to a dataframe that is filled with a bunch of strings when you meant to include numerical data such as floats and ints.
 
