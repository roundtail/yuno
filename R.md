
# General

In a dataframe a variable is a category, and observations are all the values under a certain variable.

# Syntax

## Vectors
*variable_name = c (item1, item2, item3)* - vector

*variable_name = data.frame (Vector1, Vector2)* - dataframe (basically a matrix)
*dataframe_name$Vector3 = c (item1, item2, items3)* - adding vectors to a dataframe
*dataframe_name = rbind (DataFrame1, DataFrame2)* - adding two dataframes together
*variable_name = subset (DataFrame, variable = "observation")* - taking out a slice of a dataframe
*DataFrame [c ("variable1", "variable2")]* - printing out only the specified vectors of a dataframe

*str (DataFrame)* - gets you the structure of a dataframe
*summary (DataFrame)* - gets you a summary of a dataframe (similar to str but more detail)
*summary (DataFrame$variable)* - summary of a specific variable in a dataframe
*DataFrame$variable* - prints out all the observations under the designated variable
*nrow (DataFrame)* - number of rows in a dataframe

*mean(DataFrame$variable)* - calculates the mean of all the variable observations
*sd(DataFrame$variable)* - standard deviation
*which.min (DataFrame$variable)* - find the min observation inside the specified variable
*which.max (DataFrame$variable)* - find the max observation inside the specified variable


## General

*getwd ()* - get current directory location

## I/O

*variable_name = read.csv ("file_name.csv")* - reads a csv file
*write.csv (DataFrameName, "filename.csv")*
*rm (filename)* - removes a file from the currecnt directory


## Plot

*plot (DataFrame$variableX, variableY)* - plots the xy graph
*hist (DataFrame$variableX)* - a histogram graph
*boxplot (DataFrame$variableX)* - a boxplot graph
*boxplot (DataFrame$ variablex ~ DataFrame $ variabley)* - boxplot in relation to 
			*xlab = ""* - x axis name
			*ylab = ""* - y axis name
			*main = ""* - plot title
*table (DataFrame$variable)* - creates a table for each observation and corresponding value
*tapply (DataFrame$variable, DataFrame $variable, method)* - creates a custom table where the second argument tells us what to group the information by

