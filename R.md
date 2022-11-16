
# General

In a dataframe a variable is a category, and observations are all the values under a certain variable.

# Syntax

## Vectors
*variable_name = c (item1, item2, item3)* - vector

*variable_name = data.frame (Vector1, Vector2)* - dataframe (basically a matrix)
*dataframe_name$Vector3 = c (item1, item2, items3)* - adding vectors to a dataframe
*dataframe_name = rbind (DataFrame1, DataFrame2)* - adding two dataframes together
*variable_name = subset (DataFrame, variable = "observation")* - taking out a slice of a dataframe

*str (DataFrame)* - gets you the structure of a dataframe
*summary (DataFrame)* - gets you a summary of a dataframe (similar to str but more detail)

## General

*getwd ()* - get current directory location

## I/O

*variable_name = read.csv ("file_name.csv")* - reads a csv file
*write.csv (DataFrameName, "filename.csv")*
*rm (filename)* - removes a file from the currecnt directory

