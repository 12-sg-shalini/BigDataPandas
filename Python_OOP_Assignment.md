## Python OOP Assignment
Q1. What is the purpose of Python's OOP?
Ans-1.Object-Oriented Programming makes the program easy to understand as well as efficient.

Q2. Where does an inheritance search look for an attribute?
Ans-2. An inheritance search looks for an attribute first in the instance object, then in the class the instance was created from, then in all higher superclasses, progressing from left to right (by default). The search stops at the first place the attribute is found.

Q3. How do you distinguish between a class object and an instance object?
Ans-3.A class is a type of blueprint that you can use to make objects. A concrete 'thing' that you constructed using a certain class is an object, which is an instance of a class. So, while the terms 'object' and 'instance' are interchangeable, the term 'instance' refers to an object's relationship to its class. for ex-
// Class House describes what a house is
class House {
    // ...
}

// You can use class House to create objects (instances of class House)
House myHouse = new House();
House sistersresidence = new House();
The class House defines what a house is, and there are specific, concrete houses that are objects and instances of this class.

Q4. What makes the first argument in a class’s method function special?
Self represents the instance of the class. By using the “self”  we can access the attributes and methods of the class in Python. It binds the attributes with the given arguments. The reason you need to use self. is because Python does not use the @ syntax to refer to instance attributes.

Q5. What is the purpose of the init method?
Ans-5.We need a constructor to initialize the data members of the class when a class is instantiated. Similar to methods, a constructor also contains the collection of statements that are executed as soon as the Object is created. The init is always called whenever we initiate a class.
for ex-
# initialising class
class Demo:

	# defining a constructor
	def __init__(self, name):

		self.name = name
		print("Initialised value is", self.name)


# Driver code
obj1 = Demo("GFG")
obj2 = Demo("Geeks")
obj3 = Demo("GeeksForGeeks")

Q6. What is the process for creating a class instance?
Ans-6.To create instances of a class, you call the class using class name and pass in whatever arguments its __init__ method accepts.

You access the object's attributes using the dot (.) operator with object. Class variable would be accessed using class name as follows −

emp1.displayEmployee()
emp2.displayEmployee()
print "Total Employee %d" % Employee.empCount
Example
Now, putting all the concepts together −

 Live Demo

#!/usr/bin/python
class Employee:
   'Common base class for all employees'
   empCount = 0
   def __init__(self, name, salary):
      self.name = name
      self.salary = salary
      Employee.empCount += 1
   def displayCount(self):
   print "Total Employee %d" % Employee.empCount
   def displayEmployee(self):
      print "Name : ", self.name, ", Salary: ", self.salary
"This would create first object of Employee class"
emp1 = Employee("Zara", 2000)
"This would create second object of Employee class"
emp2 = Employee("Manni", 5000)
emp1.displayEmployee()
emp2.displayEmployee()
print "Total Employee %d" % Employee.empCount

Q7. What is the process for creating a class?
Ans-7.The class statement creates a new class definition. The name of the class immediately follows the keyword class followed by a colon as follows −

class ClassName:
'Optional class documentation string'
class_suite
Example
class Employee:
   'Common base class for all employees'
   empCount = 0
   def __init__(self, name, salary):
      self.name = name
      self.salary = salary
      Employee.empCount += 1
   def displayCount(self):
      print "Total Employee %d" % Employee.empCount
   def displayEmployee(self):
      print "Name : ", self.name, ", Salary: ", self.salary

Q8. How would you define the superclasses of a class?
Ans-8.A superclass is the class from which many subclasses can be created. The subclasses inherit the characteristics of a superclass. The superclass is also known as the parent class or base class.

Q9. What is the relationship between classes and modules?
Ans-9.The difference between a class and a module in python is that a class is used to define a blueprint for a given object, whereas a module is used to reuse a given piece of code inside another program.
Q10. How do you make instances and classes?
Ans-10.To create instances of a class, you call the class using class name and pass in whatever arguments its __init__ method accepts.

"This would create first object of Employee class"
emp1 = Employee("Zara", 2000)
"This would create second object of Employee class"
emp2 = Employee("Manni", 5000)
You access the object's attributes using the dot (.) operator with object. Class variable would be accessed using class name as follows −

emp1.displayEmployee()
emp2.displayEmployee()
print "Total Employee %d" % Employee.empCount

Q11. Where and how should be class attributes created?
Ans-11

Q12. Where and how are instance attributes created?

Q13. What does the term "self" in a Python class mean?

Q14. How does a Python class handle operator overloading?

Q15. When do you consider allowing operator overloading of your classes?

Q16. What is the most popular form of operator overloading?

Q17. What are the two most important concepts to grasp in order to comprehend Python OOP code?

Q18. Describe three applications for exception processing.

Q19. What happens if you don't do something extra to treat an exception?

Q20. What are your options for recovering from an exception in your script?

Q21. Describe two methods for triggering exceptions in your script.

Q22. Identify two methods for specifying actions to be executed at termination time, regardless of  
whether or not an exception exists.

Q23. What is the purpose of the try statement?

Q24. What are the two most popular try statement variations?

Q25. What is the purpose of the raise statement?

Q26. What does the assert statement do, and what other statement is it like?

Q27. What is the purpose of the with/as argument, and what other statement is it like?

Q28. What are *args, **kwargs?

Q29. How can I pass optional or keyword parameters from one function to another?

Q30. What are Lambda Functions?

Q31. Explain Inheritance in Python with an example?

Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of 
class C, which version gets invoked?

Q33. Which methods/functions do we use to determine the type of instance and inheritance?

Q34.Explain the use of the 'nonlocal' keyword in Python.

Q35. What is the global keyword?
