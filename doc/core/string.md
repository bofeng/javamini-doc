# String
### How to Declare a String
You can declare a String in 3 different ways.
##### char
You can create a char[] array to represent a String.
```java
char[] s1 = {'H', 'e', 'l', 'l', 'o'};
```
##### Strings
You can create a String object.  
```java
String s2 = new String("Hello");
```
##### String literals
You can create a String using String literals.  
A String literal is something that is contained within quotation marks.
```java
String s3 = "Hello";
```

##### Difference between String and String Literal
The difference between a String and a String Literal is that when assigned, if two String literals are created, it would point to the same reference in memory. For a String, if there is a new object created, it always creates a new reference.

```java
String s4 = "Hello";
String s5 = "Hello";
String s6 = new String("Hello");
String s7 = new String("Hello");

System.out.println(s4 == s5);
//Prints true because they share the same memory address
System.out.println(s4 == s7);
//Prints false because s6 creates a String object with a different memory address
System.out.println(s6 == s7);
//Prints false because s6 and s7 are both String objects created with different memory addresses
```
### String concatenation
String concatentation can be done in two ways.  
##### concat() Method
You use the method as follows:
s1 = s1.concat("s2");
s1 is the original String and s2 is the String you want to concatenate with.

```java
String s1 = new String("Hello");
s1 = s1.concat(" There");
System.out.println(s1); //Prints out "Hello There"
```

##### + operator
```java
String s2 = "Hi";
s2 = s2 + ", Hello There";
System.out.println(s2); //Prints "Hi, Hello There"
```
### Escape Sequences
Escape sequences have specific meanings to a compiler.
##### \"
Inserts a quotation mark into a String.
##### \\
Inserts a backslash into a String.
##### \n
Inserts a newline into a String.

```java
String s = "\\\"Hello\"\\";
System.out.println(s); //Prints out \"Hello"\

String ss = "Hi\nHello";
System.out.println(ss);
//Prints out
//Hi
//Hello
```
### equals() vs. compareTo()
Both equals() and compareTo() compares 2 objects.
###### equals()
The equals() method is from the Object class. It tells the user is "equal to" another String. It returns true if the contents of the String is the same.
```java
String sss1 = "Java";
String sss2 = "Python";
String sss3 = "Java";
System.out.println(sss1.equals(sss3));
//Prints true because the contents of sss1 and sss3 both say "Java".
System.out.println(sss1.equals(sss2));
//Prints false because one String is Java and the other is Python.
```
###### compareTo()
The compareTo() method is from the Comparable interface. It tells the user if it is greater than, equal to or less than another String. A negative integer is returned if the String is less than the String specified. It returns 0 if the String is equal to the specified String. A positive integer is returned if the String is greater than the String specified.  

<b>Note:</b> Greater than refers to later in the alphabet and less than refers to earlier in the alphabet. Lowercase letters are considered later in the alphabet. It compares two strings, using the ASCII values for each character. For example, 'H' < 'T' and 'T' < 'b'. To see the table of ASCII characters, [click here](http://www.asciitable.com/). In the first table, the number under "Dec" is the number for that character. Therefore characters that appear later in the list are greater than those that appear before.
```java
String ss1 = "Hello";
String ss2 = "Hi";
String ss3 = "There";
String ss4 = "Hi";
System.out.println(ss2.compareTo(ss3));
//Returns a negative integer since ss2 comes before ss3 alphabetically (ss2 is less than ss3).
System.out.println(ss2.compareTo(ss1));
//Returns a positive integer since ss2 comes after ss1 alphabetically (ss2 is greater than ss1).
System.out.println(ss2.compareTo(ss4));
//Returns 0 because ss2 is equal to ss4.
```
