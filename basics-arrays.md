Arrays [] 

## Creating and Initializing
int[] myArray = {1,2,3,4,5}; //Creating, initilizing, and populating an array all in one line
int[] myArray; // Creating an array

## #Multi-Dimensional Arrays
String[][] myMultiArray = {{name1, name2},{age1, age2}}; //Creating an array of arrays

## Copying Arrays
### System.arraycopy();
int[] original = {1, 2, 3, 4, 5};
int[] copy = new int[original.length];
System.arraycopy(original, 0, copy, 0, original.length);

### .clone(); 
int[] original = {1,2,3,4,5};
int[] copy = original.clone(); 

## Handy Array Methods
.binarySearch()
.equals()
.fill()
.sort()
.parallelSort()
.stream()
.toString()

### .binarySearch(); 
Search for a specific value and get the index of it's position // NOTE! Array needs to be sorted for binarySearch to work! 
int[] numbers = {1, 3, 5, 7, 9, 11, 13, 15};

  int searchFor = 7;
  int result = Arrays.binarySearch(numbers, searchFor);

  if (result >= 0) {
      System.out.println(searchFor + " found at index " + result);
  } else {
      System.out.println(searchFor + " not found. Insertion point: " + (-result - 1));
  }

### .length
Use the .length to find the length of an array. .length isn't actually a method - so you dont have to add parentheses. 

int[] numbers = {1,2,3,4}; 

System.out.println(numbers.length);

## 2D Arrays
Think of them as an array of arrays. Rows and Columns. 

//initialize a 2D Array with 3 rows and 3 columns

String[][] cars = new Array[3][3]

or

String[][] cars = {
                    {"Corvette", "Chevrolet", "Mustang"}.
                    {"Toyota", "Suzuki", "Mitsubishi"},
                    {"Kia", "Hyundai", "Daihatsu"}
                    }
                
// iterate through array

    for(int i=0; i<cars.length; i++){ // iterates through the rows
      System.out.println();
      for(int j=0; j<cars[0].length; j++){ // iterates through the columns
        System.out.print(cars[i][j] + " " );
      }
    }

