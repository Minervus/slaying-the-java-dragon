# Data Types
int myNum = 5;               // *Integer (whole number)
float myFloatNum = 5.99f;    // Floating point number
double myDouble = 5.123098123912 // More precise than a float
char myLetter = 'D';         // Character
boolean myBool = true;       // Boolean
String myText = "Hello";     // String (reference, not primitive)

## Typecasting Variables

public class Main {
  public static void main(String[] args) {
    double myDouble = 9.78d;
    int myInt = (int) myDouble; // Casting the double variable as an int using (int)

    System.out.println(myDouble);   // Outputs 9.78
    System.out.println(myInt);      // Outputs 9
  }
}

