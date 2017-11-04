#Exceptions
An exception is defined as "is an event, which occurs during the execution of a program, that disrupts the normal flow of the program's instructions". This means that something that shouldn't have happened in your program happened and the program has been terminated. 

##Types of Exceptions
###ArithmeticException  
This exception is thrown when the math attempting to be calculated is not a valid arithmetic calculation, ie. if you try to divide a number by 0.

###NullPointerException  
This exception is thrown when a program tries to call an object but the object is null, ie. if an object is attempted to be modified, but the object is null. 

###IndexOutOfBoundsException  
An index that is called in any object that is not in bounds or out of range. The index is either less than zero or greater than size - 1. 

###ArrayIndexOutOfBoundsException  
The ArrayIndexOutOfBoundsException is a specific instance of the IndexOutOfBoundsException. It is thrown specificially when an index that is referenced from an array is not in bounds or out of range. The index is either less than zero or greater than size - 1. 

###IllegalArgumentException  
This exception is thrown to show that the argument, or parameter, passed into a method is inapproriate or invalid.  