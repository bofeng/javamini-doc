#Number
Numbers of Java are all primitive types in Java.  

##Types of Numbers in Java
There are **integer** types and **IEEE-754 floating point** types.  
An _integer_ is a number that is a positive or negative whole number or 0.  
An _IEEE-754 floating point_ is a number that can be an integer or decimal values between them.  

###Integer Types
* ```byte```: This is the smallest type of number in Java and is a signed 8-bit two's complement integer (this value takes _one byte_). It has a minimum value of -128 and a maximum value of 127.
* ```short```: This is a signed 16-bit two's complement integer (this value takes _two bytes_). It has a minimum value of -32768 and a maximum value of 32767.  
* ```int```: This is a signed 32-bit two's complement integer (this value takes _four bytes_). It has a minimum value of -2<sup>31</sup> and a maximum value of 2<sup>31</sup>-1.  
* ```long```: This is a signed 64-bit two's complement integer (this value takes _eight bytes_). It has a minimum value of -2<sup>63</sup> and a maximum value of 2<sup>63</sup>-1.

###IEEE-754 Floating Point
* ```float```: This is a signed single-precision 32-bit IEEE-754 floating point number. The range is hard to be defined.
```java
float f = 123.5f;
```  
**Note:** A floating point declaration must have a "f" at the end of the assigned value to indicate the value is a float and not a double number, as demonstrated below.  

* ```double```: This is a signed double-precision 64-bit IEEE-754 floating point number. The range is hard to be defined. This type can hold smaller and larger values than the type of number.

---
##How to Cast Numbers
You can make it so that a smaller number is placed in a larger type _without_ explicit casting. The rules are as follows:

* byte to short, int, long, float, or double  
* short to int, long, float, or double  
* int to long, float, or double  
* long to float or double  
* float to double  

<span style="color:blue">**Example**</span>    
```java
byte x = 105;
long s = x; //Sets the long value "s" to "x" or 105.
float f = s; //Sets the float value "f" to "s" or 105.0.
```

Explicit casting is needed to convert from larger types to smaller types, ie. anything not included in the list above. Usually, double to any type or short to byte.  
The values have to be explicitly cast because the program may be **losing** information so the values have to be explicitly cast. Note that when you cast a double or float (a number with a decimal) to an integer, no rounding occurs. It simply drops all the digits after the decimal point and leaves you with the integer portion of the number.

<span style="color:blue">**Example**</span>    
```java
double x = 235.054;
long s = (int) x; // Sets the long value "s" to "x" as an integer or 235.
float f = s; //Sets the float value "f" to "s" or 235.0.
```
