# Data-Science-Journey
Libraries covered so far..
1. Numpy
2. Pandas

## Numpy Topics
1. What is Numpy?
2. What are the benefits of Numpy?
3. Why we need Numpy?
4. What is Contiguous allocation in memory
5. What is Boolean selection?
6. What is Sliceability?
7. What is Vectorized operation?
8. Example(to see the benefits of Contimuous Allocation of memory and Vectorize operation. The following example calculates the time required by the for loop in Python to square a list consisting of 100,000 sequential integers)
### Operations in Numpy:
1. Creating NumPy arrays
2. Method 01 : A NumPy array can be created using multiple techniques. The following code creates a new NumPy array object from a Python list:
3. Method 2: We can create a python range into numpyy array
4. Method 03: Making "a range" starting at 0 and with 10 values np.arange(0, 10)
5. finding the type of array, size of array, dimension, shape or array and dtype of elements
6. Increamenting by 2 from number 0 to 10
7. Reverse Counting
8. Evenly spaced #'s between two intervals
9. Converting /Cast Data type of ndarray
10. Casting floating point into integer data type
## Pandas Topics
### *Working with Series in Pandas
1. Create one item Series
2. Create a series of multiple items using a list
3. getting the values in the Series
4. getting the index of the Series
5. Explicitly Creating index(which are string but not integar)
6. Accesssing value by label, Accesssing value by integar
7. Create Series from an existing index(scalar value with be copied at each index label)
8. Creating Series from dict
9. Creating Series from numpy array
10. Checking Size, shape, uniqueness, and counts of values
11. Peeking at data with heads, tails, and take
12. Lable lookup(get multiple item from Series)
13. Position Bases lookup(get multiple item from Series)
14. Series with an integer index, but not starting with 0
15. label-based lookup versus position-based lookup
16. Using loc and iloc
17. Alignment via index labels
18. Concatinate Series(Using Dictionary and extra item from another Series)
19. Concatinating Series(if the series has duplicate index)
20. Handling(the case of Not-A-Number) with Series
21. Series handle NaN values like NumPy
22. ***Working Boolean Selection
23. select rows where values are > 5
24. A little shorter version to Select
25. Select specific range of rows from series
26. Getting sum of values by giving boolean indexing
27. Get all item those satisfy the condition
28. Get any of those item that satisfy the condition
29. count values that satisfy the condition
30. Reindexing a Series
31. Changing indexes of a series
32. Concatinating Series
33. Reset index(duplication of index may be remove)
34. Using reindex() method to reindex
35. Concatinating string and integar labels
36. fill with Some Value instead of NaN
37. ForwardFill BackWordFill and nearest
38. Slicing a Series
##### [39. first five by slicing, same as .head(5)](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/70f49288e9c592b0704855a61213faa09310f484/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [40. Missing Data in Series](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/d027fa6a1782edc81969d8300e803db818374a28/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [41. Check if series has null values](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/b6f6eb9813717269d93454e26e5dcd2768d57440/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [42. Check if series has not null values(return true)](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/5d1c930a1dc9c3ea7bb63804990b96af88c5b0d8/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [43. The pandas DataFrame Object](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/f777322269cf34daf671dbe058366a137b2662ee/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [44. Creating a DataFrame from scratch](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/fbb1aeac5483ea48c150ff8a143c26ee4a725ff0/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [45. Create a DataFrame for a list of Series objects](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/9a71ec5f84e51318a1fe4bf0086eb77cd03b2553/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [46. Create a DataFrame with two Series objects in dictionary](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/310bceea6e53f866176881696d94cc48fe8fd438/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [47. Create a DataFrame with named columns and rows](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/3813f244d16271cd05e0290292cf51df5e637a3a/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [48. Demonstrate alignment during creation](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/3813f244d16271cd05e0290292cf51df5e637a3a/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [49. Creating data frames(using dictionary)](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/20de00ba5c2676b18abc71705749b44813163355/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [50. Accessing Each Column](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/445ffbfb17b17e5381fbcc69ce7b1f5790576427/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [51. Adding new column to old dataframe](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/acb367e1116d576050fa33a3773b35e27427f80c/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [52. Assigning value to new column](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/8eded8388a5c3b8e8cfebed800a790f96e9bfafe/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [53. Assigning value to dataframe using Series](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/67aba85a556f9777051c94f665b1d3db93895abe/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [54. Adding new column with boolean value](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/d1a11daf428bbf9e81c0cc47ca062eda6ec29a98/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [55. Deleting Column](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/326679c5204d7ab873a0e77a880202caeb80b9f9/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [56. Adding data in the form of nested dictionary](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/7e22e666981fe907968cb9c5e3139ea0c1d1f752/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [57. Making Row as column and column as row (Taking Transpose)](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/86613dcd5ef320d69fcc5be36472b9163f744fab/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
