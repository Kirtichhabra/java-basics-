# java-basics-
Welcome to my repository of basic Java programs! In this collection, you'll find a variety of simple programs written in Java that are perfect for beginners who are just getting started with coding.


# 1. Print Hello World in Java :panda_face:

```java
public class HelloWorld{
public static void main(String[] args){
System.out.println("HelloWorld");
    }    
}
```
public class HelloWorld{

public static void main(String[] args){


System.out.println("HelloWorld");

    }
    
}

# 2. How to Add & Product two Integers 	:panda_face:

#### The java.util package is a part of the Java Standard Library that provides a set of utility classes and interfaces for performing various tasks, such as manipulating arrays, working with dates, handling collections of objects, and more. It contains commonly used data structures like ArrayList, LinkedList, HashMap, HashSet, etc., which can be used to store and manipulate collections of objects.

### Some of the classes and interfaces provided by the java.util package include:
ArrayList, LinkedList, Vector: for storing and manipulating lists of objects
Scanner: for reading input from the console or other sources

## Here is the CODE :polar_bear: 


import java.util.Scanner;

public class Add&Product

public static void main(String[] args){

 Scanner in = new Scanner(System.in);
 
 System.out.println("Input the First Number")
 
 int firstInt = in.nextInt();
 
 System.out.println("Input the Second Number")
 
 int SecondInt = in.nextInt();
 
 
System.out.println("Sum of integers :",firstInt + SecondInt);

System.out.println("Product of integers :",firstInt*SecondInt);

    }
    
} 


# 3. How to Add & Product of two Integers :dog:

public class SumProduct2 {

    public static void main(String[] args) {
    
       int firstVariable,secondVariable;
       
       firstVariable = 20;
       
       secondVariable = 30;
       
       
        System.out.println("Sum is "+(firstVariable+secondVariable));
        
        System.out.println("Product is "+(firstVariable*secondVariable));
        
   
     }
     
}

# 4. How to check number is even or odd using if - else loop 	:smiley_cat:

import java.util.Scanner;

public class ifelse{

public static void main(String[] args){

Scanner scanner = new Scanner(System.in);

 System.out.println("Input the num1");
 
 int num1 = scanner.nextInt();
 
 if (num1%2==0)
 
 {
 
 System.out.println("num1 is even");
 
  }
  
 else
 
 {
 
 System.out.println("num1 is odd");
 
         }
      
     }
  
}

# 5. How to Convert Celsius to Fahrenhiet 	:ghost:

import java.util.Scanner;

public class Convertor{

public static void main(String[] args){

Scanner scanner = new Scanner(System.in);

 System.out.println("Input the Celsius Unit");
 
 int celsius = scanner.nextInt();
 
 double Fahrenheit = ((celsius * 1.8) + 32);
 
 System.out.println(Fahrenheit);
 
      }
      
}
 
 
# 6. How to find the Power of a Number :astonished:
 
 public class Exponent{
 
public static void main(String[] args){

double base = 17;

int exponent = 2

double result = Math.pow(base, exponent);

int exponent1 = 3;

double result1 = Math.pow(base, exponent1);

System.out.println("The value of result is:" +result);

System.out.println("The value of result is:" +result1);

    }
    
}

# Switch Case :mask: :-

## In Java, a switch case is a control statement used to execute different blocks of code based on the value of a variable or expression.

# Here is the Code :flushed: :-

# 7. Find out Whether the number is prime or composite :sunglasses:

public class TypeofNumber{

public static void main(String[] args){

int num = 4;

String result = "";

switch (num){

case 1: 

result = "number is neither composite and nor prime";

 break;
 
case 2: 

result = "number is prime"; 

break;

case 4: 

result = "number is composite";

break;

default:

result = "Not a Correct option";

break;

    }
    
System.out.println(result);

      }
   
  }
