,# Python Resources

## The Web
- [Python.org](https://www.python.org/)
- [Python on GitHub](https://github.com/python)

## Selected Books 
- Matthes, Eric. Python Crash Course, 2nd Ed. or later, published by No Starch Press.

# Python and computer science for non programmers

If you're new to computer programming, python is probably the best language to start with. Following are short lessons and examples intended to supplement existing resources for new programmers and Python.

## Lists and Arrays, Tuples and Ranges, Vectors, Matrices and Sets

These are are sequential data structures or can be represented by sequential data structures.

### Lists

A Python list is the same thing as an array in other languages, like c/c++. Python lists are generally more convenient to use as they don't require memory allocation or specific typing.

A simple Python list is like your grocery list. It's a one-dimensional array. Entries in the list are indexed numerically from 0 to the number of entries minus one (0,1,2...n-1).

```
grocery_list=["cereal","milk","orange juice"]
```
A longer form of this is:
```
grocery_list=[]
grocery_list[0]="cereal"
grocery_list[1]="milk"
grocery_list[2]="orange juice"
```
The first line lets the Python interpreter know that `grocery_list` is a list.

## Example: Is it a dog?

This example combines Python lists, Boolean algebra, and vectors to make a very simple AI.

```
a_dog=["barks","has fur","has four legs",'wags its tail"]
bv=[False,False,False,False]
if bv[0] and bv[1] and bv[2] and bv[3] :
    is_a_dog=True
else:
    is_a_dog=False
```








