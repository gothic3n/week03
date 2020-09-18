# week03
Week 03 assigment

Members:

Frank Munoz

Erica Wisniewski

1. What are JDK, JRE and JVM? It should be in your own words and not more than two unambiguous sentences for each.

The JDK is the Java Development Kit. It is the tools necessary to compile and debug java code.
The JRE is the java Runtime Environment. It is the tools necessary to run compiled java code.
The JVM is the Java Virtual Machine. It is a tool that interfaces between the software and hardware of the machine that is running the java compiled code.

2. What is the relation between the three (JDK, JRE, JVM)? How is Java code executed in a Java program. Explain by assuming that the program was written on one platform (e.g., Windows) and executed on another (e.g., Linux). Small paragraph of 6-9 sentences.

The JDK, JRE, and JVM interact with each other to make a java program and run it. The JDK is used to compile the code into what is called bytecode. Then this bytecode is run on the JRE which includes the JVM within it that runs the bytecode. The JVM runs the bytecode converting it to machine language that the particular computer system understands. For example code could have been written and compiled on a windows machine using the JDK. then that compiled bytecode could be moved to a linux machine and run using that linux machine's version of the JRE. Once run in that linux machine JRE the JVM of the JRE would be invoked to take the bytecode and convert the bytecode into machine language that the linux machine can run as if it were a native linux application.

3. With the help of the code for Hello World program in Java (you can copy code with citation), explain when this program needs JDK (and not JRE and JVM), JRE (and not JVM) and JVM.

```
/* This is a simple Java program. 
   FileName : "HelloWorld.java". */
class HelloWorld 
{ 
    // Your program begins with a call to main(). 
    // Prints "Hello, World" to the terminal window. 
    public static void main(String args[]) 
    { 
        System.out.println("Hello, World"); 
    } 
} 
```
Citation:
Beginning Java programming with Hello World Example. (2018, July 13). Retrieved September 17, 2020, from https://www.geeksforgeeks.org/beginning-java-programming-with-hello-world-example/


The "Hello World" program above uses JDK, JRE, and JVM to run. The program uses the JDK to compile and run the java code within the file. If a developer was going to try to debug this code, they would also be using the JDK in this regard. The JRE - or runtime environment - will contain the class libraries and is responsible for loading classes and making sure this is correctly working with Java libraries. So we are using "System" in this program, which is a class that includes standard I/O and file accessing. The JRE would make sure this class can be used. The JRE also responsible for the JVM, which is used at runtime by making sure the running application, in this case "Hello World", has the proper resources to run, like memory. So for this program, we are passing a string to println() which in turn will print our string, this could involve allocating memory to pass this string to println, or memory to contain our specific instruction set which will set our string and any instructions involved in the Java class function call.

4. Modify the document at least twice each person to make it better and show your competency to do version control using github.





