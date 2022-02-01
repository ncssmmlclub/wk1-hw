# 1. Functions/Input
- Write a function `contains(s1,s2)` where `s1` and `s2` are string that are inputted by the user and returns `true` if `s2` is a contiguous substring of `s1`
```python
contains("coward", "cow") -> true
contains("abcdef", "acf") -> false
contains("moose", "") -> true
```
# 2. NumPy/Pandas
## Pandas
1. Create a dataframe with columns A B C D E F and 10 rows
2. Have column A count from 1 through 10
3. Have column B count from 10 through 1
4. Have column C be the number 7
5. Have columns D E F be random numbers
## Numpy
1. Create a 2x4 array filled with random numbers
2. Transpose this array
3. Select the middle two elements in each column and add another dimension to the result
4. Select all elements in the 0th column
5. Print the 0th element of the last dimension
# 3. OOP
- Create a class with the following:
1. init method/constructor that reads the txt file in the directory and creates a new instance variable with the data
2. method `word_count()` that returns a list of tuples with each sentence and the number of words in it
3. method `first_position(list_of_tuples)` that takes that list of tuples and returns a dictionary with the count of each letter found in the sentence (letter string : count int)
