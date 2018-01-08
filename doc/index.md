## What's Java?

Java is an interpreted programming language that is object oriented. Many programming languages like C and C++ are compiled languages, this means that the computer goes through the code, translates it into a binary instruction set for the specific computer architecture of the computer running the program, then runs the machine code. This means that a C or C++ program can be translated (compiled) totally differently depending on the machine it is being ran on. Java is much different, as previously stated Java is interpreted (translated) into what is known as byte code, which is compiled by the Java virtual machine (JVM) that compiles any byte code the same regardless of computer architecture.

Java is an extremely popular and powerful programming language. It is one of the first languages usually taught on a computer science track and is widely supported for many different uses. Java can be used for game design using libraries like FXGL or Greenfoot, Java even has some game libraries akin to Unity and Unreal like LibGDX used for powerful 3D game development. Java can also be used to parse massive amounts of data, make applets and plugins on web pages, and even describe hardware using JHDL, Java's Hardware Description Library.

The world is slowly gravitating away from the verbosity of languages like Java but it is a great stepping stone and after learning Java, developing your skills in any other language will be a breeze. This is not to say Java is irrelevant, Java is the main programming language of everything Android and any Android developer on the app store got there through the use of Java code (most likely in the Android Studios IDE). Java is also and will most likely continue to be the High-School level standard for programming languages and advanced knowledge is useful for college accolades specifically the AP Java Test.

## About JavaMini

JavaMini is an application built into the OYOclass platform which can be used to write Java code following the guidelines for the AP Computer Science A exam. It cannot do everything that can be done using the Java programming language. It is limited to simple standard input and output and the Java standard libraries. It is designed to allow you to run Java code in the browser, making storage and sharing your work easier.

You cannot use it to make user interfaces or games with dynamic input. All input must be entered into the small box at the bottom of the output window (where it says "Expand Standard Input/User Input") *before* running the program.

## Quick Start

Copy following example code to JavaMini editor then click the "Run" button:

* Say hello

```java
public class Hello{
    public static void main(String[] args) {
        System.out.println("Hello Java");
    }
}
```

* Calculator

```java
public class Calculator {
    public static void main(String[] args) {
        // declare and initialize two values
        int a = 10;
        int b = 5;
        // basic mathematical operations
        System.out.println(a + b); // add
        System.out.println(a - b); // subtract
        System.out.println(a * b); // multiply
        System.out.println(a / b); // divide
        System.out.println(a + a / b); // mixed
    }
}
```

## Beyond JavaMini

If you would like to do more with Java and go beyond the capabilities of Java Mini, please download and install the JDK (Java Development Kit) and a Java IDE (Integrated Development Environment) which you can find links to below:

* To download the JDK, [Click here](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
* To download the Eclipse IDE, [Click here](http://www.eclipse.org/downloads/eclipse-packages/),
  * In the orange bar, choose your operating system (Windows, Mac OS X, or Linux)
  * Click where it says "64 bit" next to "Eclipse IDE for Java Developers"
* To download the Netbeans IDE, [Click here](https://netbeans.org/downloads/)
  * Underneath the first column, where it says "Java SE", click on the Download button
* If you download the JDK from above, you are probably using JDK 8. Java Mini uses JDK 7. There aren't too many differences. [Click here](https://docs.oracle.com/javase/7/docs/api/) for the documentation for Java 7.
