## Typecasting
Used to assign a value of one primitave data type to another type

### Widening casting
Converting a SMALLER type to a LARGER type 

int myInt = 9; 
double myDouble = myInt; // Widening casting is done automatically by Java

System.out.println(myDouble); //Outputs 9.0 - Automatically converted the int to a double

### Narrowing casting
Converting a larger data type into a smaller one - more tricky

double myDouble = 9.78; 
int myInt = (int) myDouble; // Needs to be explicitly stated with the (int)

System.out.println(myInt); //Output - 9 - trims off the double into an int

