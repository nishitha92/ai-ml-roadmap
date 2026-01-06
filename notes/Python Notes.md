# Python
Python is a high-level, dynamically typed multiparadigm programming language. Python code is often said to be almost like a pseudocode, since it allows you to express very powerful ideas in a few lines of code. 

Python has a number of basic types including integers, floats, booleans and strings. These data types behave in ways that are familiar from other programming languages. Python implements all of the usual operators for Boolean logic, but uses English words rather than the symbols (&&, ||, etc).

## Python includes several built-in container types: 
### Lists 
A list is the Python equivalent of an array, but is resizable and can contain elements of different types. 

````python

xs = [1,2,3]
print(xs, xs[2])
print(xs[-1])

````

In addition to accessing list elements one at a time, python provides concise syntax to access sublists; this is known as slicing. 

### Dictionaries 
A dictionary stores (key, value) pairs, similar to a Map in Java or an object in Javascript. 

````python

d = {'cat' : 'cute', 'dog' : 'furry'}
print(d['cat'])

````


### Sets
A set is an unordered collection of distinct elements. 

````python

animals = {'cat', 'dog'}
print('cat' in animals) # check if an element is in a set; print "True"

````


### Tuples
A Tuple is an ordered list of values. A Tuple is in many ways similar to list; one of the most important differences is that tuples can be used as keys in dictionaries and as elements of sets, while lists cannot. 

````python
t = (5, 6)
print(type(t))
````

