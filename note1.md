# Object oriented Programing note 1

i think OOP is awesome!

```python

# Example class

class person:

    def __init__(self, name):
        self.name = name
    
    def __str__(Self):
        return f"person object called: {self.name}"
   
   def __repr__(self):
        returnself.__str__()


```

## Definitions
-Encapsulation: Hiding or resteriction of access to information, represented as 2 underscores as a prefix, setter and getter methods are used to interact with encapsulated attributes.
-Polymorphism: A method that can be used with many classes and object that is dependant on its variables,
-Overrides: Two methods with the same name and parameters, one method is the parent while the other is the child, the child class can provide implementation for a method that exists in the parent class, both magic-methods and base funcitons can be overridden.
-OOP concept: as if making a blueprint that the program can later call, in a class variables are called 'atributes' and functions are called 'methods', Upper case names are reserved for classes. __repr__ must be used to make the code printable.
## General notes
__init__:The init method is a special method in Python that is used to initialize the attributes of an object when it is created. 
__str__: a special method in Python that is used to define a string representation of an object.
__repr__ should be used whenever __str__ is.
Super() can be used to call an inheritance.
Self is always used as a keyword to call an instance of a class.
Global variables must be avoided as much as possible.
A child class does not need __init__ unless it requires new attributes.
__iter__(): allows the object to be iterable.
__next__(): allows us to get to the next value when iterating.
Encapsulation should be used when hiding informtion and preventing the editing of important code by the user.

