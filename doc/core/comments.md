#Comments
All types of comments are ignored by the Java Compiler. Comments are used for the user's own clarity as well as other user's clarity if there is collaboration on various projects.

###Different Type of Comments

* ```// text ``` : This is a comment where the compiler ignores everything from the "//" to the end of the line
* ```/* text */``` : This is a comment where the compiler ignores everything enclosed by the "/\*" and "*/". These type of quotes can span multiple lines.
* ```/** text */``` : This notation is specifically for Javadoc. This is a comment where the compiler ignores everything enclosed by the "**/\*\***" and "***/**". These type of documentation usually spans multiple lines.

<span style="color:blue">**Example**</span>    
```java
System.out.println("Hello"); //Prints "Hello" and the information after the // won't throw an error

int x = 14;
/*
	x = 15; //This does not set a new value for x
	System.out.println(x); //This is not printed
*/

System.out.println(x); //This would print out 14

/* You can also do this - it does not have to be a multi-lined comment.*/
```

###Javadoc
Javadoc is used by many programmers as a way to easily identify different parts of a function. It usually includes a short description about the function, @param and @return values. All of this information would be enclosed in "**/\*\***" and "**\*/**" notation.  

######Javadoc Documentation######
*   ```@param```:  "param" is short for parameter. This would denote the _types_ of parameters that are used in a particular function along with a short description of the parameter.  
*   ```@return```: This gives a description of what is being returned from the function.

<span style="color:blue">**Example**</span>    
```java
/**
* 	This function multiplies two integers.
*	@param a the first integer that is being multiplied
*	@param b the second integer that is being multiplied
*	@return	the product of multiplying a and b together
*
*/
public static int multiply(int a, int b){
	return a*b;
}
```
