# **0x0A. Python - Inheritance**

# **Task 0. Lookup, File: 0-lookup.py** 
 Writing a function that returns the list of available attributes and methods of an object: Prototype: def lookup(obj): Returns a list object. You are not allowed to import any module.

# **Task 1. My list, File: 1-my_list.py, tests/1-my_list.txt:**
 Writing a class MyList that inherits from list: Public instance method: def print_sorted(self): that prints the list, but sorted (ascending sort). You can assume that all the elements of the list will be of type int. You are not allowed to import any module.

# **Task 2. Exact same object, File: 2-is_same_class.py:**
 Writing a function that returns True if the object is exactly an instance of the specified class ; otherwise False. Prototype: def is_same_class(obj, a_class): You are not allowed to import any module.

# **Task 3. Same class or inherit from, File: 3-is_kind_of_class.py:**
 Writing a function that returns True if the object is an instance of, or if the object is an instance of a class that inherited from, the specified class ; otherwise False. Prototype: def is_kind_of_class(obj, a_class): You are not allowed to import any module.

# **Task 4. Only sub class of, File: 4-inherits_from.py:**
 Writing a function that returns True if the object is an instance of a class that inherited (directly or indirectly) from the specified class ; otherwise False. Prototype: def inherits_from(obj, a_class): You are not allowed to import any module.

# **Task 5. Geometry module, File: 5-base_geometry.py:**
Writing an empty class BaseGeometry. You are not allowed to import any module.

# **Task 6. Improve Geometry, File: 6-base_geometry.py:**
 Writing a class BaseGeometry (based on 5-base_geometry.py). Public instance method: def area(self): that raises an Exception with the message area() is not implemented. You are not allowed to import any module.

# **Task 7. Integer validator, File: 7-base_geometry.py, tests/7-base_geometry.txt**
 tests/7-base_geometry.txt: Writing a class BaseGeometry (based on 6-base_geometry.py). Public instance method: def area(self): that raises an Exception with the message area() is not implemented. Public instance method: def integer_validator(self, name, value): that validates value: you can assume name is always a string. if value is not an integer: raise a TypeError exception, with the message must be an integer. if value is less or equal to 0: raise a ValueError exception with the message must be greater than 0. You are not allowed to import any module.

# **Task 8. Rectangle, File: 8-rectangle.py**
 Writing a class Rectangle that inherits from BaseGeometry (7-base_geometry.py). Instantiation with width and height: def init(self, width, height): width and height must be private. No getter or setter. width and height must be positive integers, validated by integer_validator.

# **Task 9. Full rectangle, File: 9-rectangle.py**
 Writing a class Rectangle that inherits from BaseGeometry (7-base_geometry.py). (task based on 8-rectangle.py) Instantiation with width and height: def init(self, width, height):: width and height must be private. No getter or setter. width and height must be positive integers validated by integer_validator. the area() method must be implemented. print() should print, and str() should return, the following rectangle description: [Rectangle] /.

# **Task 10. Square #1, File: 10-square.py**
 Writing a class Square that inherits from Rectangle (9-rectangle.py): Instantiation with size: def init(self, size):: size must be private. No getter or setter. size must be a positive integer, validated by integer_validator. the area() method must be implemented.

# **Task 11. Square #2, File: 11-square.py**
 Writing a class Square that inherits from Rectangle (9-rectangle.py). (task based on 10-square.py). Instantiation with size: def init(self, size):: size must be private. No getter or setter. size must be a positive integer, validated by integer_validator. the area() method must be implemented. print() should print, and str() should return, the square description: [Square] /.

# **Task 12. My integer, File: 100-my_int.py**
 Writing a class MyInt that inherits from int: MyInt is a rebel. MyInt has == and != operators inverted. You are not allowed to import any module.

# **Task 13. Can I?, File: 101-add_attribute.py**
 Writing a function that adds a new attribute to an object if it’s possible: Raise a TypeError exception, with the message can't add new attribute if the object can’t have new attribute. You are not allowed to use try/except. You are not allowed to import any module.
