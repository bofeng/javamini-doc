#Operators
##Arithmetic Operators
* ```+```: if a + b, you add the two together
* ```-```: if a - b, you subtract b from a
* ```*```: if a * b, you multiply a and b
* ```/```: if a / b, you divide a by b
* ```%```: if a & b, you return the remainder after a / b
---
##Incrementing or Decrementing
* ```++```: if a++, you increase a by 1
* ```--```: if a--, you decrease b by 1
---
##Assignment
* ```=```: if a = 10, you set the value of a to 10
* ```+=```: if a += b, you set the value of a to the original value of a + b
* ```-=```: if a -= b, you set the value of a to the original value of a - b
* ```*=```: if a *= b, you set the value of a to the original value of a * b
* ```/=```: if a /= b, you set the value of a to the original value of a / b
* ```%=```: if a %= b, you set the value of a to the original value of a % b

<span style="color:blue">**Example**</span>    
```java
int a = 14;
a++; //This changes a to 15
a /= 3; //This changes a to 5
a %= 2; //This changes a to 1

int c = a + 8; //This sets c to 1 + 8 = 9
c *= 2; //This sets c to 18
```

<span style="color:blue">**Example**</span>
```java
int a = 14;
int x = a-- + --a;
// a++ will use 14 in the addition, subtracts 1 from a, now a = 13
// --a will first subtract 1 from a, so a = 12,
// then it will add 14 to 12 and get 26
System.out.println("a = " + a);
System.out.println("x = " + x);
```
