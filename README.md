# LIST
```
✅ What is a List?

A list is a mutable, ordered collection of items.
Items can be of any data type (integers, strings, objects, even other lists).
Defined using square brackets []

- list are heterogenous
- list can have duplicate type of data
- list are ordered
- list are mutable/changable
```
### 🧠 Key Features:
- Ordered	Items maintain insertion order
- Mutable	Can be changed (add, update, delete)
- Indexed	Accessed using index (starting at 0)
- Dynamic	Size can grow/shrink
- Heterogeneous	Can store mixed data types

###  List Creation
```python
empty_list = []
numbers = [1, 2, 3, 4]
mixed = [1, "Python", 3.14]
nested = [[1, 2], [3, 4]]
```
###  Accessing Elements
Indexing
- Accessing elements of a list using position numbers (called indices).

- Indexing starts at 0 in Python.

- You can use positive and negative indices.


``` python
my_list = ['a', 'b', 'c', 'd']

print(my_list[0])    # 'a'
print(my_list[2])    # 'c'
print(my_list[-1])   # 'd' (last item)
print(my_list[-2])   # 'c' (second last)

```
### Slicing:
- Getting a portion (sublist) from a list using a range of indices.
``` python
my_list = [10, 20, 30, 40, 50, 60]
print(my_list[1:4])      # [20, 30, 40]
print(my_list[:3])       # [10, 20, 30] (from start)
print(my_list[3:])       # [40, 50, 60] (till end)
print(my_list[::2])      # [10, 30, 50] (every 2nd)
print(my_list[::-1])     # [60, 50, 40, 30, 20, 10] (reverse list)
```
### 📘 Useful List Methods in Python

#### append() :
```python
l = [1, 2, 3]
l.append(4)
print(l)  # [1, 2, 3, 4]
```
---
#### extend() :
```python
l = [1, 2]
l.extend([3, 4])
print(l)  # [1, 2, 3, 4]
```
---
#### insert() :
```python
l = [1, 2, 4]
l.insert(2, 3)
print(l)  # [1, 2, 3, 4]
```
---
#### remove() :
```python
l = [1, 2, 3, 2]
l.remove(2)
print(l)  # [1, 3, 2] (first 2 is removed)
```
---
#### pop() :
```python
l = [10, 20, 30]
x = l.pop()
print(x)  # 30
print(l)  # [10, 20]

y = l.pop(0)
print(y)  # 10
```
---
#### index() :
```python
l = [5, 10, 15]
print(l.index(10))  # 1
```
