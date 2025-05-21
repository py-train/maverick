# Exercise

This exercise is based on the movie titles dataset. This dataset comes from https://developer.imdb.com/non-commercial-datasets/




```python
# Load the titles.csv file into a pyspark dataframe


```


```python
# Explore the columns in the dataframe


```


```python
# Check if the datatypes have been correctly inferred


```


```python
# The runtime column specifies the length of the movie in minutes
# Calculate the total runtime of all movies in the dataset


```


```python
# Calculate the minimum, maximum and average runtime


```

## Fun fact

- What value do you get for the **maximum**? Doesn't it appear like an outlier? Or is it?
- https://en.wikipedia.org/wiki/Logistics_(film)


```python
# Find the title of the movie with the maximum runtime


```


```python
# The isAdult column indicates if the movie has adult content
# Calculate the count of movies that are maked as adult


```


```python
# The dataset give data for movies from the very start of movie making
# That's more than 100 years of data!

# Calculate counts of movies made per year


```


```python
# The movie titles are typically multiple words
# Extract the first word of the titles (Hint: '\w+' in regexp indicates a word)


```


```python
# The genre column indicates one or more genres that the movie lies in
# Find all Comedy movies (i.e. all movies that include the comedy genre
# (Hine: col('colname').contains(...)


```

## Challenge Question


```python
# The generes column has a comma separated list of genres that the movie belongs to
# But what is the comprehensive list of unique genres that are present in this dataset?
# Can they be collected into an output python list like : ['Coemdy', 'Drama', ..]?
# (Hint keywords: split, array, explode, ..


```
