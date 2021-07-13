# Day 2 #
Youtube Link: [Link](https://youtu.be/GA0u6WM7_Eo)
- Boolean variable and operations.
- Strings and string operations.
- A data structure called List (represented as []).
  1. Lists can have duplicates.
  1. `list.append(object)` inserts object at the end of the list unformatted.
  2. `list.insert(object, index)` inserts object at the specified index unformatted.
  3. `list.extend(object)` inserts objects with formatting (if the specified object is a list, inserts the objects in it instead of appending it as list).
  3. `object[index]` retrieves object at the specified index.
  4. `object[indexstart:indexend]` return a new list from specifed start until before end index.
  5. `sum(object=list)` returns the sum of all the objects.
  6. `list.pop(index)` returns and removes the object at the specified index (if not removes the last object) of the list.
  7. `list.count(object)` returns the of occurances of the specified object.
  8. `list.index(object, startindex, endindex)` return the index of the specifed object within startindex and endindex (if specified).
  9. `max(object=list)` returns the maximum element of the list.
  1. `min(object=list)` returns the minimum element of the list.
  2. ```python 
     [1,2,'apple'] * 2 => [1, 2, 'apple', 1, 2, 'apple']
     ```
Youtube Link: [Link](https://youtu.be/wlS_fWxIPyQ)
- Sets, a collection of non repeating objects which is constucted in a way we can only retrive data through operations (meaning can't retrive item through index).
  1. Set works like a Set in maths, where opeation like intersection, diffrence can be performed.
  2. Defined as `{"object"}`.
- Dictionary, same as a hash table, defined as `{"key":"value"}`.
- Tuples, collection of constants, defined with `("object")`.
- > NOTE: Items inside a Dictionary are saved as tuples.
