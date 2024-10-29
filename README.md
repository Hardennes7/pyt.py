# pyt.py


 void main() {
  // 1. Define Variables
  int myInt = 42;
  double myDouble = 3.14;
  String myString = "Hello, Dart!";
  bool myBool = true;
  List<int> myList = [1, 2, 3, 4, 5];

  // Print variable values
  print("Integer: $myInt");
  print("Double: $myDouble");
  print("String: $myString");
  print("Boolean: $myBool");
  print("List: $myList");

  // 2. Type Conversion
  print("\nType Conversion:");
  convertAndDisplay("123");
  convertAndDisplay("45.67");

  // 3. Control Flow: If-Else Statements
  print("\nControl Flow - If-Else:");
  checkNumber(-10);
  checkVotingEligibility(17);

  // 4. Switch Case
  print("\nControl Flow - Switch Case:");
  printDayOfWeek(3); // Example for Wednesday

  // 5. Loops
  print("\nControl Flow - Loops:");
  printNumbersUsingForLoop();
  printNumbersUsingWhileLoop();
  printNumbersUsingDoWhileLoop();

  // 6. Combining Data Types and Control Flow
  print("\nCombining Data Types and Control Flow:");
  List<int> numbers = [5, 12, 3, 44, 101];
  categorizeAndPrintNumbers(numbers);
}

// Function to convert String to int and double
void convertAndDisplay(String numberString) {
  int intValue = int.parse(numberString);
  double doubleValue = double.parse(numberString);
  print("Converted String '$numberString' to int: $intValue and double: $doubleValue");
}

// Function to check if a number is positive, negative, or zero
void checkNumber(int number) {
  if (number > 0) {
    print("The number $number is positive.");
  } else if (number < 0) {
    print("The number $number is negative.");
  } else {
    print("The number is zero.");
  }
}

// Function to check voting eligibility
void checkVotingEligibility(int age) {
  if (age >= 18) {
    print("Person is eligible to vote.");
  } else {
    print("Person is not eligible to vote.");
  }
}

// Function to print day of the week
void printDayOfWeek(int day) {
  switch (day) {
    case 1:
      print("Monday");
      break;
    case 2:
      print("Tuesday");
      break;
    case 3:
      print("Wednesday");
      break;
    case 4:
      print("Thursday");
      break;
    case 5:
      print("Friday");
      break;
    case 6:
      print("Saturday");
      break;
    case 7:
      print("Sunday");
      break;
    default:
      print("Invalid day");
  }
}

// Function using a for loop to print numbers from 1 to 10
void printNumbersUsingForLoop() {
  for (int i = 1; i <= 10; i++) {
    print(i);
  }
}

// Function using a while loop to print numbers from 10 to 1
void printNumbersUsingWhileLoop() {
  int i = 10;
  while (i >= 1) {
    print(i);
    i--;
  }
}

// Function using a do-while loop to print numbers from 1 to 5
void printNumbersUsingDoWhileLoop() {
  int i = 1;
  do {
    print(i);
    i++;
  } while (i <= 5);
}

// Function to categorize and print numbers from a list
void categorizeAndPrintNumbers(List<int> numbers) {
  for (int number in numbers) {
    print("Number: $number");

    // Check if even or odd
    if (number % 2 == 0) {
      print("Even");
    } else {
      print("Odd");
    }

    // Categorize using switch statement
    switch (number) {
      case 1:
      case 2:
      case 3:
      case 4:
      case 5:
      case 6:
      case 7:
      case 8:
      case 9:
      case 10:
        print("Category: Small");
        break;
      case 11:
      case 12:
      case 13:
      case 14:
      case 15:
      case 16:
      case 17:
      case 18:
      case 19:
      case 20:
      case 21:
      case 22:
      case 23:
      case 24:
      case 25:
      case 26:
      case 27:
      case 28:
      case 29:
      case 30:
      case 31:
      case 32:
      case 33:
      case 34:
      case 35:
      case 36:
      case 37:
      case 38:
      case 39:
      case 40:
      case 41:
      case 42:
      case 43:
      case 44:
      case 45:
      case 46:
      case 47:
      case 48:
      case 49:
      case 50:
      case 51:
      case 52:
      case 53:
      case 54:
      case 55:
      case 56:
      case 57:
      case 58:
      case 59:
      case 60:
      case 61:
      case 62:
      case 63:
      case 64:
      case 65:
      case 66:
      case 67:
      case 68:
      case 69:
      case 70:
      case 71:
      case 72:
      case 73:
      case 74:
      case 75:
      case 76:
      case 77:
      case 78:
      case 79:
      case 80:
      case 81:
      case 82:
      case 83:
      case 84:
      case 85:
      case 86:
      case 87:
      case 88:
      case 89:
      case 90:
      case 91:
      case 92:
      case 93:
      case 94:
      case 95:
      case 96:
      case 97:
      case 98:
      case 99:
      case 100:
        print("Category: Medium");
        break;
      default:
        print("Category: Large");
    }
  }
}

 
