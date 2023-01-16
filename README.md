# Advanced-programming-for-data-science
### Question 1
a. Write a class called Student that has two instance variables, name and mark, and one class variable, passingMark. Assign 50 to passingMark. Within the class, you need to code the __init__ and __str__ methods. The __str__ method returns the name and mark of the Student’s class object.
b. Next, write an instance method called passOrFail() within the Student class. This method returns the string “Pass” if mark is greater than or equal to passingMark or “Fail” if mark is lower than passingMark.
c. Outside the class, instantiate a Student object called student1 with name = 'John' and mark = 52 as parameters, and use it to call the passOrFail() method. Assign the result to a variable called status1 and print the value of status1.
d. Instantiate another Student object called student2 with name = 'Jenny' and mark = 69 as parameters, and use it to call the passOrFail() method. Assign the result to a variable called status2 and print the value of status2.
Update the value of passingMark to 60 for all instances of the Student class and call the passOrFail() method for student1 and student2 again. Assign the results to status1 and status2 respectively and print the two values.

### Question 2
Design a class Message that models an e-mail message. A message has a recipient, a sender, and a message text. Support the following methods:
✓ A constructor that takes the sender and recipient
✓ A method get_sender that returns the sender’s name
✓ A method get_recipient that returns the recipient’s name
✓ A method append that appends a line of text to the message body
✓ A method toString that makes the message into one long string like this: "From: Harry Morgan\nTo: Rudolf Reindeer\n . . ."
Write a program that uses this class to make a message and print it.

### Question 3
Make a class Employee with a name and salary. Make a class Manager that inherits from Employee. Add an instance variable, named department, to the Manager class that stores a string. Supply a method _ _repr_ _ that prints the manager’s name, department, and salary. Note that you need to use _ _ repr_ _ method in the Employee class to print the name and salary. Write a program that uses these classes to create a manager object and print its information.

### Question 4 
Write a program that asks a user to type in two strings and that prints
a. the characters that occur in both strings.
b. the characters that occur in one string but not the other.
c. the letters that don’t occur in either string.
Write three different functions to do the tasks above.
# Sample Run:
- Enter the first string: Python
- Enter the second string: Programming
### - Shared characters:
P, n, o
### - Unique characters:
a, g, h, i, m, r, t, y
### - Non-occuring alphabet letters:
b, c, d, e, f, j, k, l, p, q, s, u, v, w, x, z

### Question 5
Using your own words, discuss Functional Programming paradigm in Python. Explain when and how to use it. You need to provide examples to support your explanations.

### Question 6
Using your own words, compare iterators, generators, and decorators in Python. You may need to provide examples to support your explanations.
