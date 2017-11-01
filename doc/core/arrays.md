# 1-Dimensional Arrays

**How to Declare an Array**  
It is declared in the following format:  
type[] name: the type represents the type of variable ie. int, and the name is the name of the new array
```
int[] arr1; #Creates an array called arr1 that holds integer values
float[] arr2; #Creates an array called arr2 that holds floating-point values
```
---
**How to Initialize the Size of an Array**  
In Java, you must declare the size of the array. If not, the size will _always_ be zero.

* type[] name;  
  name = new type[size];  
  You declare the array first and then you create the size of the array after the declaration.

```
int[] arr1; #This is the initial declaration of an array.
arr1 = new int[2]; #This sets the newly created array to size 2.
```

* type[] name = new type[size]: You declare and initialize the array in the same line, and make an array of a type that has a certain size.

```
int[] arr2 = new int[10]; #This makes an array that can hold 10 integers.
String[] arr3 = new String[5]; #This makes an array that can hold 5 Strings.
```
---
**How to Reference the Indices in an Array**  
The indices of an array start at 0. So, the first element of an array would be at the 0th position.  
The highest position would then be _size - 1_.
```
int[] arr4 = new int[20];
arr4[1] = 20; #Sets the 2nd integer in the array to 20.
arr4[0] = 40; #Sets the 1st integer in the array to 40.

String[] arr5 = new String[25];
arr5[0] = "Hi"; #Sets the 1st indice to "Hi"
```

# 2-Dimensional Arrays

# Initializing Arrays with a List