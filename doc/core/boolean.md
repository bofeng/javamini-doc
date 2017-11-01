#Boolean
Booleans are used to show the logical values of _true_ and _false_.  

**Constants **   
&nbsp;&nbsp; -- true  
&nbsp;&nbsp; -- false  

###Logical Operators
* ```!``` : Negates the value; For !x, if x is **true**, then !x is _false_. If x is **false**, then !x is _true_.
* ```&&``` : If x && y, if both is **true**, then x && y is _true_, else x && y is _false_.
* ```||``` : If x || y, if both is **false**, then x || y is _false_, else x || y is _true_.

<span style="color:blue">**Example**</span>     
```
boolean x = true; //Sets the value of x to true
boolean y = false; //Sets the value of y to false
System.out.println(!x); //Prints false
System.out.println(!y); //Prints true
System.out.println(x&&x); //Prints true
System.out.println(x&&y); //Prints false
System.out.println(y&&y); //Prints false
System.out.println(x||x); //Prints true
System.out.println(x||y); //Prints true
System.out.println(y||y); //Prints false
```

###Comparison Operators
* ```==``` : equal
* ```!=``` : not equal
* ```<``` : strictly less than
* ```<=``` : less than or equal to
* ```>``` : strictly greater than
* ```>=``` : greater than or equal to

<span style="color:blue">**Example**</span>    
```
System.out.println(45 == 45); //Prints true
System.out.println(45 != 45); //Prints false
System.out.println(45 >= 34); //Prints true
System.out.println(45 >= 45); //Prints true
System.out.println(45 > 23); //Prints true
System.out.println(45 > 45); //Prints false
System.out.println(34 <= 23); //Prints false
System.out.println(34 < 34); //Prints false
```

###Object Comparison
There are two ways to compare two objects. One way is using the "==" comparison and the other way is using the .equals() function that exists in objects.  

** == **  
The "==" is used to compare when primitive values, boolean, byte, char, double, int, float, short, and byte, are equal.It only checks if two values point to the same reference and does not check if the contents in the reference is the same.      

** .equals() **
The ".equals()" is used to compare when two objects are equal, such as Strings. It checks if the contents within the reference are the same. A user cannot use .equals() function to check if primitive values are the same because primitive values cannot be dereferenced.  


<span style="color:blue">**Example**</span>    
```
boolean x = 56; 
System.out.println(x == 56);//Prints true
String str1 = "Hello"; //Creates a new String called "Hello"
String str2 = new String("Hello"); //Creates a new String called "Hello"
System.out.println(str1 == str2); //Prints false
System.out.println(str1.equals(str2)); //Prints true 
```