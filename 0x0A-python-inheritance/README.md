#0x0A. Python - Inheritance

In this project, I learned about Python class inheritance. I learned about the differences between super- and sub-classes while practicing inheritance, definining classes with multiple base classes, and overiding inherited methods and attributes.
#Resources i use for learing the topic 
<a href='https://www.youtube.com/watch?v=d8kCdLCi6Lk'>Inheritance Magic Methods</A>
<a href='https://docs.python.org/3/tutorial/classes.html#inheritance'>Inheritance</A>
<a href='https://docs.python.org/3/tutorial/classes.html#multiple-inheritance'>Multiple inheritance</A>
<a href='https://www.geeksforgeeks.org/inheritance-in-python/'>Inheritance in Python</A>
Prototypes for functions written in this project:
| File                    | Prototype                             |
| ----------------------- | ------------------------------------- |
| `0-lookup.py`           | `def lookup(obj):`                    |
| `2-is_same_class.py`    | `def is_same_class(obj, a_class):`    |
| `3-is_kind_of_class.py` | `def is_kind_of_class(obj, a_class):` |
| `4-inherits_from.py`    | `def inherits_from(obj, a_class):`    |
| `101-add_attribute.py`  | `def add_attribute(obj, att, value):` |

Tasks i will solve 

task --> 0. Lookup
  * Python function that returns a list of available attributes and methods of an objects.

task --> 1. My list
  * Python class `MyList` that inherits from `list`. Includes:
    Public instance method `def print_sorted(self):` that prints the list in ascending sorted order (assumes all list elements are `int`s).

task --> 2. Exact same object
  * Python function that returns `True` if an object is exactly an instance of a specified class; otherwise `False`.

task --> 3. Same class or inherit from
  * Python function that returns `True` if an object is an instance or inherited instance of a specified class; otherwise `False`.

task --> 4. Only sub class of
  * Python function that returns `True` if an object is an inherited instance (either directly or indirectly) from a specified class; otherwise `False`.

task --> 5. Geometry module
  * An empty Python class `BaseGeometry`.

task --> 6. Improve Geometry
  * Python class `BaseGeometry`. Builds on  with:
    Public instance method `def area(self):` that raises an `Exception` with
    the message `area() is not implemented`.

task --> 7. Integer validator
  * Python class `BaseGeometry`. Builds on with:
    Public instance method `def integer_validator(self, name, value):` that validates the parameter `value`.
    Assumes the parameter `name` is always a string.
    The parameter `value` must be an `int`, otherwise, a `TypeError` exception is raised with the message `<name> must be an integer`.
    The parameter `value` must be greater than `0`, otherwise, a `ValueError` exception is raised with the message `<value> must be greater than 0`.

task --> 8. Rectangle
  * Python class `Rectangle` that inherits from `BaseGeometry` -
  Includes:
    Private attributes `width` and `height` - validated with `integer_validator`.
    Instantiation with `width` and `height`: `def __init__(self, width, height):`

task --> 9. Full rectangle
  * Python class `Rectangle` that inherits from `BaseGeometry` Builds 
    Implementation of the method `area()`.
    Special method `__str__` to print `Rectangle`s in the format `[Rectangle] <width>/<height>`.

task --> 10. Square 
  * Python class `Square` that inherits from `Rectangle` . 
  Includes:
    Private attribute `size` - validated with `integer_validator`.
    Instantiation with `size`: `def __init__(self, size):`.
    Implementation of the `area()` method.

task --> 11. Square
  * Python class `Square` that inherits from `Rectangle` 
    Special method `__str__` to print squares in the format `[Square] <width>/<height>`.

task --> 12. My integer
  * Python class `MyInt` that inherits from `int`. Includes:
    Inversion of the `==` and `!=` operators.

task --> 13. Can I?
  * Python function that adds a new attribute to an object if possible.
    If an attribute cannot be added, a `TypeError` exception is raised with the message `can't add new attribute`.
