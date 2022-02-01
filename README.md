- You can go to [colab](https://colab.research.google.com/) and create an environment from this repo, the landing page has a github tab
- You can also click the "open in Visual Studio Code" button to edit locally and save changes automatically
- Or, you can simply download the code by clicking on the code button & Download ZIP (although we'd recommend cloning with the GitHub CLI or SSH), edit locally and click the "add file" button to upload your compeleted notebook

# 1. Functions/Input
- Write a function `contains(s1,s2)` where `s1` and `s2` are strings that are inputted by the user that returns `true` if `s2` is a contiguous substring of `s1`
```python
def contains(s1: str, s2: str) -> bool
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
```python
def word_count() -> List[tuple(str,int)]
```
3. method `first_position(list_of_tuples)` that takes that list of tuples and returns a list of dictionaries with the count of each letter found in the sentence
```python
def first_position(sentences List[tuple(str,int)]) -> List[dict{str : int}]
```
