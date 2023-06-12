# ScannerInJava

- Scanner is used to take the inputs from the end user. The end user is the computer

Syntax: 

  Scanner s = new Scanner(System.in);
  
  
  We basically create a new object called Scanner.
  
  - We use "System.in" to take the input from the end user. 


To read int data we use "nextInt()"


Ex:

Scanner s = new Scanner(System.in);

int num = s.nextInt();

______________________________________
To read byte data we use "nextByte()"


Ex:

Scanner s = new Scanner(System.in);

byte num = s.nextByte();


______________________________________
To read long data we use "nextLong()"


Ex:

Scanner s = new Scanner(System.in);

long num = s.nextLong();


______________________________________
To read float data we use "nextFloat()"


Ex:

Scanner s = new Scanner(System.in);

float num = s.nextFloat();

______________________________________
To read double data we use "nextDouble()"


Ex:

Scanner s = new Scanner(System.in);

double num = s.nextDouble();


______________________________________
To read String data we use "nextInt()"


Ex:

Scanner s = new Scanner(System.in);

String abc = s.next();

- next() will only take the first line of words and not the full line


- To get the full line we use nextLine()


## Note: We have to import Scanner. 

 - Scanner is a class name that is available in java.util package.

It would look like 

import java.util.Scanner;
