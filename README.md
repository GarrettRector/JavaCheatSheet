Cheat Sheet
=============================

Java Cheat Sheet is just a bunch of Java syntax/examples

# Java Information

Java is a [OOP](https://en.wikipedia.org/wiki/Object-oriented_programming) Language 
(Object Orientated Programming), which means the language is based off [objects](#objects). 
These objects can be [Variables](#variables), [Methods](#methods), a million other things.
Data types are also a big part of Java as well as every other programming language, which are
[Primitive data types]() and [Non-Primitive data types](), which happen to be the two main 

# Syntax

A lot of IDEs will cover Basic syntax, but I will cover a lot of it here:
* Any Phrase in Java will require a semicolon (;) after it
* Unlike Python, [Methods](#methods) use Curly Brackets {}, instead of colons (:)
    ```java
    public class Methods {
      public void main(String[] args) {
          System.out.println("Java Examples");
      }
* [Classifiers](#classifiers) are used for both methods and for variables, and are required for Java.
* For 

# Variables
To Do

# Methods
Methods are a part of java that allows you to run multiple pieces of code at once, and require

# Classifiers
To Do

# Objects
Objects composed of [Primitive data types](#primitive-data-types) and [Non-Primitive data types](#non-primitive-data-types)
and can be used to describe everything in Java because it is a OOP language, and is focused on Objects.

# Primitive Data Types

A primitive data type specifies the size and type of variable values, and it has no additional methods.

There are eight primitive data types in Java:

| Data Type | Size          | Description
| :-------: | :-----------: | :--------:
| byte	    | 1 byte	    | Stores whole numbers from -128 to 127
| short	    | 2 bytes	    | Stores whole numbers from -32,768 to 32,767
| int	    | 4 bytes	    | Stores whole numbers from -2,147,483,648 to 2,147,483,647
| long	    | 8 bytes	    | Stores whole numbers from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807
| float	    | 4 bytes	    | Stores fractional numbers. Sufficient for storing 6 to 7 decimal digits
| double    | 8 bytes	    | Stores fractional numbers. Sufficient for storing 15 decimal digits
| boolean   | 1 bit	        | Stores true or false values
| char	    | 2 bytes	    | Stores a single character/letter or ASCII values
# Number Types
Primitive number types are divided into two groups:
  
Integer types stores whole numbers, positive or negative (such as 123 or -456), without decimals. Valid types are byte, short, int and long. Which type you should use, depends on the numeric value.
  
Floating point types represents numbers with a fractional part, containing one or more decimals. There are two types: float and double.

# Integer Types
### Byte
The byte data type can store whole numbers from -128 to 127. This can be used instead of int or other integer types to save memory when you are certain that the value will be within -128 and 127:
```java
public class Bytes {
  public static void main(String[] args) {
    byte myNum = 100;
    System.out.println(myNum);
  }
}
```
### Short
The short data type can store whole numbers from -32768 to 32767:
```java
public class Shorts {
  public static void main(String[] args) {
    short myNum = 5000;
    System.out.println(myNum); 
  }
}
```
### Int
The int data type can store whole numbers from -2147483648 to 2147483647. In general, and in our tutorial, the int data type is the preferred data type when we create variables with a numeric value.
```java
public class Integers {
  public static void main(String[] args) {
    int myNum = 100000;
    System.out.println(myNum);  
  }
}
```
### Long
The long data type can store whole numbers from -9223372036854775808 to 9223372036854775807. This is used when int is not large enough to store the value. Note that you should end the value with an "L":
```java
public class Long {
  public static void main(String[] args) {
    long myNum = 15000000000L;
    System.out.println(myNum);  
  }
}
```
# Floating Point Types
You should use a floating point type whenever you need a number with a decimal, such as 9.99 or 3.14515.

### Float
The float data type can store fractional numbers from 3.4e−038 to 3.4e+038. Note that you should end the value with an "f":
```java
public class Floats {
  public static void main(String[] args) {
    float myNum = 5.75f;
    System.out.println(myNum);  
  }
}
```
### Double
The double data type can store fractional numbers from 1.7e−308 to 1.7e+308. Note that you should end the value with a "d":
```java
public class Double {
  public static void main(String[] args) {
    double myNum = 19.99d;
    System.out.println(myNum);  
  }
}
```
### Scientific Numbers
A floating point number can also be a scientific number with an "e" to indicate the power of 10:
```java
public class Scientific {
  public static void main(String[] args) {
    float f1 = 35e3f;
    double d1 = 12E4d;
    System.out.println(f1);
    System.out.println(d1);  
  }
}
```
# Booleans
A boolean data type is declared with the boolean keyword and can only take the values true or false:

Do Note that Booleans in Java have to be either "true" or "false" lowercase and without quotes
```java
public class Boolean {
  public static void main(String[] args) {
    boolean True = true;
    boolean False = false;    
    System.out.println(True);
    System.out.println(False);
  }
}
```

# Non-Primitive Data Types
