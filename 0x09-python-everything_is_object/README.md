# **0x09. Python - Everything is object**

In this project I learnt,
Why Python programming is awesome
What is an object
What is the difference between a class and an object or instance
What is the difference between immutable object and mutable object
What is a reference
What is an assignment
What is an alias
How to know if two variables are identical
How to know if two variables are linked to the same object
How to display the variable identifier (which is the memory address in the CPython implementation)
What is mutable and immutable
What are the built-in mutable types
What are the built-in immutable types
How does Python pass variables to functions

# **Task 0. Who am I?, 0-answer.txt**
What function would you use to print the type of an object?
Write the name of the function in the file, without ().

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 0-answer.txt

# **Task 1. Where are you?, 1-answer.txt**
How do you get the variable identifier (which is the memory address in the CPython implementation)?
Write the name of the function in the file, without ().

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 1-answer.txt

# **Task 2. Right count, 2-answer.txt**
In the following code, do a and b point to the same object? Answer with Yes or No.

>>> a = 89
>>> b = 100

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 2-answer.txt

# **Task 3. Right count =, 3-answer.txt**
In the following code, do a and b point to the same object? Answer with Yes or No.

>>> a = 89
>>> b = 89

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 3-answer.txt

# **Task 4. Right count =, 4-answer.txt**
In the following code, do a and b point to the same object? Answer with Yes or No.

>>> a = 89
>>> b = a

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 4-answer.txt

# **Task 5. Right count =+, 5-answer.txt**
In the following code, do a and b point to the same object? Answer with Yes or No.

>>> a = 89
>>> b = a + 1

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 5-answer.txt

# **Task 6. Is equal, 6-answer.txt**
What do these 3 lines print?

>>> s1 = "Best School"
>>> s2 = s1
>>> print(s1 == s2)

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 6-answer.txt

# **Task 7. Is the same, 7-answer.txt**
What do these 3 lines print?

>>> s1 = "Best"
>>> s2 = s1
>>> print(s1 is s2)

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 7-answer.txt

# **Task 8. Is really equal, 8-answer.txt**
What do these 3 lines print?

>>> s1 = "Best School"
>>> s2 = "Best School"
>>> print(s1 == s2)

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 8-answer.txt

# **Task 9. Is really the same, 9-answer.txt**
What do these 3 lines print?

>>> s1 = "Best School"
>>> s2 = "Best School"
>>> print(s1 is s2)

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 9-answer.txt

# **Task 10. And with a list, is it equal, 10-answer.txt**
What do these 3 lines print?

>>> l1 = [1, 2, 3]
>>> l2 = [1, 2, 3] 
>>> print(l1 == l2)

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 10-answer.txt

# **Task 11. And with a list, is it the same, 11-answer.txt**
What do these 3 lines print?

>>> l1 = [1, 2, 3]
>>> l2 = [1, 2, 3] 
>>> print(l1 is l2)

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 11-answer.txt

# **Task 12. And with a list, is it really equal, 12-answer.txt**
What do these 3 lines print?

>>> l1 = [1, 2, 3]
>>> l2 = l1
>>> print(l1 == l2)
Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 12-answer.txt

# **Task 13. And with a list, is it really the same, 13-answer.txt**
What do these 3 lines print?

>>> l1 = [1, 2, 3]
>>> l2 = l1
>>> print(l1 is l2)

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 13-answer.txt

# **Task 14. List append**
What does this script print?

l1 = [1, 2, 3]
l2 = l1
l1.append(4)
print(l2)

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 14-answer.txt

# **Task 15. List add**
What does this script print?

l1 = [1, 2, 3]
l2 = l1
l1 = l1 + [4]
print(l2)

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 15-answer.txt

# **16. Integer incrementation**
What does this script print?

def increment(n):
    n += 1

a = 1
increment(a)
print(a)

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 16-answer.txt

# **Task 17. List incrementation**
What does this script print?

def increment(n):
    n.append(4)

l = [1, 2, 3]
increment(l)
print(l)

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 17-answer.txt

# **Task 18. List assignation**
What does this script print?

def assign_value(n, v):
    n = v

l1 = [1, 2, 3]
l2 = [4, 5, 6]
assign_value(l1, l2)
print(l1)

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 18-answer.txt

# **Task 19. Copy a list object**
Write a function def copy_list(l): that returns a copy of a list.

The input list can contain any type of objects
Your file should be maximum 3-line long (no documentation needed)
You are not allowed to import any module

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 19-copy_list.py

# **Task 20. Tuple or not?**
a = ()
Is a a tuple? Answer with Yes or No.

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 20-answer.txt

# **Task 21. Tuple or not?**
a = (1, 2)
Is a a tuple? Answer with Yes or No.

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 21-answer.txt

# **Task 22. Tuple or not?**
a = (1)
Is a a tuple? Answer with Yes or No.

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 22-answer.txt

# **Task 23. Tuple or not?**
a = (1, )
Is a a tuple? Answer with Yes or No.

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 23-answer.txt

# **Task 24. Who I am?**
What does this script print?

a = (1)
b = (1)

a is b
Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 24-answer.txt

# **Task 25. Tuple or not**
What does this script print?

a = (1, 2)
b = (1, 2)
a is b

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 25-answer.txt

# **Task 26. Empty is not empty**
What does this script print?

a = ()
b = ()
a is b

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 26-answer.txt

# **Task 27. Still the same?**
>>> id(a)
139926795932424
>>> a
[1, 2, 3, 4]
>>> a = a + [5]
>>> id(a)
Will the last line of this script print 139926795932424? Answer with Yes or No.

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 27-answer.txt

# **Task 28. Same or not?**
>>> a
[1, 2, 3]
>>> id (a)
139926795932424
>>> a += [4]
>>> id(a)
Will the last line of this script print 139926795932424? Answer with Yes or No.

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 28-answer.txt

# **Task 29. #pythonic**
Write a function magic_string() that returns a string “BestSchool” n times the number of the iteration (see code):

Format: see example
Your file should be maximum 4-line long (no documentation needed)
You are not allowed to import any module

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 100-magic_string.py

# **Task 30. Low memory cost**
Write a class LockedClass with no class or object attribute, that prevents the user from dynamically creating new instance attributes, except if the new instance attribute is called first_name.

You are not allowed to import any module

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 101-locked_class.py

# **Task 31. int 1/3**
Assuming we are using a CPython implementation of Python3 with default options/configuration:

How many int objects are created by the execution of the first line of the script? (103-line1.txt)
How many int objects are created by the execution of the second line of the script (103-line2.txt)
Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 103-line1.txt, 103-line2.txt

# **Task 32. int 2/3**
Assuming we are using a CPython implementation of Python3 with default options/configuration:

How many int objects are created by the execution of the first line of the script? (104-line1.txt)
How many int objects are created by the execution of the second line of the script (104-line2.txt)
After the execution of line 3, is the int object pointed by a deleted? Answer with Yes or No (104-line3.txt)
After the execution of line 4, is the int object pointed by b deleted? Answer with Yes or No (104-line4.txt)
How many int objects are created by the execution of the last line of the script (104-line5.txt)

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 104-line1.txt, 104-line2.txt, 104-line3.txt, 104-line4.txt, 104-line5.txt

# **Task 33. int 3/3**
Assuming we are using a CPython implementation of Python3 with default options/configuration:

Before the execution of line 2 (print("Love")), how many int objects have been created and are still in memory? (105-line1.txt)
Why? (optional blog post :))
Hint: NSMALLPOSINTS, NSMALLNEGINTS

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 105-line1.txt

# **Task 34. Clear strings**
Assuming we are using a CPython implementation of Python3 with default options/configuration (For answers with numbers use integers, don’t spell out the word):

How many string objects are created by the execution of the first line of the script? (106-line1.txt)
How many string objects are created by the execution of the second line of the script (106-line2.txt)
After the execution of line 3, is the string object pointed by a deleted? Answer with Yes or No (106-line3.txt)
After the execution of line 4, is the string object pointed by b deleted? Answer with Yes or No (106-line4.txt)
How many string objects are created by the execution of the last line of the script (106-line5.txt)

Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x09-python-everything_is_object
File: 106-line1.txt, 106-line2.txt, 106-line3.txt, 106-line4.txt, 106-line5.txt

