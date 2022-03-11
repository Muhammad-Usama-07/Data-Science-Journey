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
##### [16. Using loc and iloc](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/6c96eedfc00af15cd1619ce2fbc0769e44757d32/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [17. Alignment via index labels](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/b6caea8f8b041abda8fd46bed4548a27d6f95fbb/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [18. Concatinate Series(Using Dictionary and extra item from another Series)](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/1e1f35031a1f7c30665428e80e664d669de80ebf/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [19. Concatinating Series(if the series has duplicate index)](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/91e4a1c55ea164a224f9051f2ef9aa488d74a42d/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [20. Handling(the case of Not-A-Number) with Series](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/9516584774b1386a418330931cc09d2e433c883b/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [21. Series handle NaN values like NumPy](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/b48c124b9f87ebf4f25a08fa0fd1f88d393f4f25/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [22. ***Working Boolean Selection](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/b7e473573ad3cb255eb0a9c9dc115c2c97d4aac7/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [23. select rows where values are > 5](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/82be42cd535146dc9dbd30800f13823f94a83d3c/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [24. A little shorter version to Select](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/180d971fa581000561561fee6ccac829be509a83/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [25. Select specific range of rows from series](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/8eb3d6cd200c865996c7ed8bb8ced74efda08eda/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [26. Getting sum of values by giving boolean indexing](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/d49ef1e6ab433abb98d97af896634a24b6c637a7/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [27. Get all item those satisfy the condition](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/320486493e6081a801bfe4a3b1e6b4ced33b8f4d/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [28. Get any of those item that satisfy the condition](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/0c33ad0ba64bc3c34db4c0198d7de101bf039a70/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [29. count values that satisfy the condition](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/81ea218a457c861c99a09a83d803c79ce20e3922/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [30. Reindexing a Series](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/14bec33bccaa78a0914af3895775ec4f1cd34c9e/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [31. Changing indexes of a series](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/e76c248b57581cfc15545ab9b0f5b65633a4be42/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [32. Concatinating Series](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/ff2143d05b56e1a96819fb1f514d98ad9db85bf8/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [33. Reset index(duplication of index may be remove)](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/031a70845a4758464e3478ca2717d856e38646d3/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [34. Using reindex() method to reindex](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/7429dd763205a66b47bdf00497fb7411b503901f/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [35. Concatinating string and integar labels](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/f735e5bbf6cdac7087ff4892cd63651f5f493f69/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [36. fill with Some Value instead of NaN](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/e2a4bef5767410d0248514ce6e7fb1cc2ae4f2aa/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [37. ForwardFill BackWordFill and nearest](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/642b8f2e9f9532f56eb5725fea6d0461c6fed39f/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
##### [38. Slicing a Series](https://github.com/Muhammad-Usama-07/Data-Science-Journey/blob/abba83fcb4abc230f1f1ecbdadd47d148b09785a/.ipynb_checkpoints/PandasWork-checkpoint.ipynb)
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
