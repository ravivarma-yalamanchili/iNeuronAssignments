## Python OOP Assignment
Q1. What is the purpose of Python's OOP?
A)	Object-Oriented Programming makes the program easy to understand as well as efficient.
	We can implement inheritance, polymorphisms, encapsulation, etc. in the programming.
	As we are writing the code in the form of modules we can reuse and maintain easyly.
	

Q2. Where does an inheritance search look for an attribute?
A)	It will first search in the child class and if not found then look in the parent class and thier superclasses.
	
Q3. How do you distinguish between a class object and an instance object?
A) 	A class is a blueprint from which objects are created. 
	An instance is a single and unique unit of a class

Q4. What makes the first argument in a class’s method function special?
A)	Self is the first argument to be passed in function Constructor and Instance Method. 
	Self must be provided as a First parameter to the Instance method
	
Q5. What is the purpose of the init method?
A)	The __init__ method lets the class initialize the object's attributes and serves no other purpose.

Q6. What is the process for creating a class instance?
A)	To create instances of a class, you call the class using class name and pass in whatever arguments its __init__ method accepts.

Q7. What is the process for creating a class?
A) 	We can use the class keyword to create class and provide aruguments if required.
	Then create a __init__ method to initialize the variables
	
Q8. How would you define the superclasses of a class?
A)	A class that is derived from another class is called a subclass (also a derived class, extended class, or child class). The class from which the subclass is derived is called a 	superclass (also a base class or a parent class)

Q9. What is the relationship between classes and modules?
A)	Modules are collections of methods and constants. They cannot generate instances. 
	Classes may generate instances (objects),and have per-instance state (instance variables).

Q10. How do you make instances and classes?
A)	you call the class using class name and pass in whatever arguments its __init__ method accepts.

Q11. Where and how should be class attributes created?
A) 	 Class attributes are the variables defined directly in the class that are shared by all objects of the class

Q12. Where and how are instance attributes created?
A)	 Instance attributes are defined in the constructor. Defined directly inside a class. Defined inside a constructor using the self parameter.

Q13. What does the term "self" in a Python class mean?
A) 	 The self parameter is a reference to the current instance of the class, and is used to access variables that belongs to the class.

Q14. How does a Python class handle operator overloading?
A) 	 The operator overloading in Python means provide extended meaning beyond their predefined operational meaning. 
	 Such as, we use the "+" operator for adding two integers as well 	 as joining two strings or merging two lists. We can achieve this as the "+" operator is overloaded by the "int" class and "str" class.

Q15. When do you consider allowing operator overloading of your classes?
A) 	 Operator overloading is mostly useful when you're making a new class that falls into an existing "Abstract Base Class" (ABC).

Q16. What is the most popular form of operator overloading?
A)	 Addition (+) operator is the most popular form of operatoroverloading.
	
Q17. What are the two most important concepts to grasp in order to comprehend Python OOP code?
A)	  inheritance and polymorphism 

Q18. Describe three applications for exception processing.
A) 	 Raised when the specified key is not found in the dictionary. 
	 Raised when an identifier is not found in the local or global namespace. 
	 Raised when trying to access a local variable in a function or method but no value has been assigned to it. 
	 Base class for all exceptions that occur outside the Python environment.
	 
Q19. What happens if you don't do something extra to treat an exception?
A) 	 The program will fail whenever we encounter any exception.

Q20. What are your options for recovering from an exception in your script?
A)	 We can implement exception handling in the program to handle the errors.

Q21. Describe two methods for triggering exceptions in your script.
A)	 Try – This method catches the exceptions raised by the program. Raise – Triggers an exception manually using custom exceptions.

Q22. Identify two methods for specifying actions to be executed at termination time, regardless of whether or not an exception exists.
A)	 else and finally can be used to run the script at ternination time.

Q23. What is the purpose of the try statement?
A)	 Try statement will help cathing the exceptions and execute exception block to handle those errors.

Q24. What are the two most popular try statement variations?
A)	 Try/Except/Finally.

Q25. What is the purpose of the raise statement?
A)	 With raise statement we can manually trigger the error in required cases.

Q26. What does the assert statement do, and what other statement is it like?
A)	 The assert keyword is used when debugging code. 
	 The assert keyword lets you test if a condition in your code returns True, if not, the program will raise an AssertionError.
	 
Q27. What is the purpose of the with/as argument, and what other statement is it like?
A)	 The with statement is a replacement for commonly used try/finally error-handling statements. 
	 A common example of using the with statement is opening a file. To open and write to a file in Python
	 
Q28. What are *args, **kwargs?
A)	 *args specifies the number of non-keyworded arguments that can be passed and the operations that can be performed on the function in Python 
	 whereas **kwargs is a variable number of keyworded arguments that can be passed to a function that can perform dictionary operations.

Q29. How can I pass optional or keyword parameters from one function to another?
A)	 By using the keyword aruguments and also specifying the argument name.

Q30. What are Lambda Functions?
A) 	 A lambda function is a small anonymous function. 
	 A lambda function can take any number of arguments, but can only have one expression.
	 
Q31. Explain Inheritance in Python with an example?
A)	 Inheritance relationship defines the classes that inherit from other classes as derived, subclass, or sub-type classes. 
	 Base class remains to be the source from which a subclass inherits. 
	 For example, you have a Base class of “Animal,” and a “Lion” is a Derived class. The inheritance will be Lion is an Animal

Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of 
class C, which version gets invoked?
A) 	 The version from class A will get invoked as we are pasiing A as the first parent class in C(A,B)

Q33. Which methods/functions do we use to determine the type of instance and inheritance?
A)	 isinstance() function,

Q34.Explain the use of the 'nonlocal' keyword in Python.
A)	The nonlocal keyword is used to work with variables inside nested functions, where the variable should not belong to the inner function. 
	Use the keyword nonlocal to declare that the variable is not local.

Q35. What is the global keyword?
A)	 The global keyword allows you to change a variable value outside of its current scope





