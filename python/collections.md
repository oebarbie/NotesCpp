# Python’s Collections

## I.	Set
  
**Main principles:**  

   - The elements’ order is not defined  
   - Elements of the set are strings and/or numbers  
   - The set cannot contain identical elements
```python
mammals = {'cat', 'dog', 'fox', 'elephant'}  
empty = set() <sub>to create an empty set</sub>  
new_elem = 'e'  
empty.add(new_elem) <sub>to add an element</sub>  
empty.clear() <sub>to clear the set</sub>  
```
**Removing the set’s element:**  

   - `pop` deletes an element and return its value  
   - `remove` deletes given element, output error if it doesn't exist  
   - `discard` deletes the given element, do **not** output error if it doesn't exist  

 **Operations with two sets:**  
 
   1.	Union (объединение)
```python
union = my_set1.union(my_set2)  
union = my_set1 | my_set2  
```
   3.	Intersection (пересечение)
```python
intersection = my_set1.intersection(my_set2)  
intersection = my_set1 & my_set2  
```
   4.	Difference (разность)
```python
diff = my_set1.difference(my_set2)  
diff = my_set1 - my_set2
```
   6.	Symmetrical Difference (симметричная разность)
```python
symm_diff = my_set1.symmetric_difference(my_set2)  
symm_diff = my_set1 ^ my_set2  
```

## II.	String  

**Main principles:**  

   - Enumeration  

## III.	Lists  

**Main principles:**  

   - The elements can be changed  
   - The elements can be values of any type  
   - The elements are ordered and indexed, a slice operation is available  
   - The elements may be repeated  
```python
list = [ ] or list = list() <sub>to create an empty list</sub>  
list = [2, 3, ‘word’]
list.append(i) <sub>to add an element</sub>  
list.extend(another list / set) <sub>expanding the list with a string or a set</sub>  
list[i] = 17 <sub>to change the element</sub>  
list[start:end] <sub>list’s cut</sub>  
del list[i], del[ ::2] <sub>removing the elements</sub>
```
