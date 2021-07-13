# Day 3 #
Video Link: [Link](https://youtu.be/vh525RjO6C0)

Installing Numpy (an array manupulation package built with C++).

- Can be initialized with a list of same datatype.
```python
arr_list = [1, 2, 3, 4]
arr = np.array(arr_list)
```
- `.shape` this lets the user the know the dimension and count along the dimension axis.
- Building multi-dimensional array
```python
arr_list1 = [1, 2, 3, 4]
arr_list2 = [5, 6, 7, 8]
arr_list3 = [9, 0, 10, 11]
arr = np.array(arr_list1, arr_list2, arr_list3)

## [[1, 2, 3, 4],
##  [5, 6, 7, 8],
##  [9, 0, 10, 11]]
```
- `.reshape(dimension1_count,..)` Can rearrange the array.
- Index referencing element 
```python
arr[element_number]       ## arr[3] => 4
arr[dimensional_position] ## arr[2,3] => 10
arr[dimensional_ranges]   ## arr[0:1, 0:1] => [[1, 2],
                          ##                   [5, 6]]
arr>3                     ## prints [true, true, false, false....., false]

## when the above condition gets passed into the index
arr[conditional]          ## arr[arr>3] => [[1, 2]]
```
- Assigning elements a value can be even done by all the above methods. `arr[:1]=2` replaces the first 2 element with 2.
- `.ones(no_of_elements, dtype=int32)` initalizes the array with unity. `dtype` specifies the datatype to be initialized with.
- `.rand(dimension_number)` selects random element from the array to fill up the specified array.
-  `.arrange(start, end, step=0)` arranges the elements within the specified range into a single dimensional array. `step` is like a multiplying factor.
- Referencing array, `arr1 = arr`, this doesn't make a copy instead references the `arr`.
- Copying array, `arr1 = arr.copy()` makes a seperate copy.
- `.linspace(start, end, no_of_elements)` auto-fill the array with the specified number of (equally incremented) elements within specified range.
