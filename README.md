# Exercises for the Helsinki Java MOOC 2020 version

#### Message Three Times
```java
// Write your program here
String message = scanner.nextLine();

System.out.println(message);
System.out.println(message);
System.out.println(message);
```

#### Greeting
```java
// Write your program here
System.out.println("What's your name?");
String name = scanner.nextLine();
System.out.println("Hi " + name);
```

#### Conversation
```java
// Write your program here
System.out.println("Greeting! How are you doing?");
String firstAnswer = scanner.nextLine();
System.out.println("Oh, how interesting. Tell me more!");
String secondAnsert = scanner.nextLine();
System.out.println("Thanks for sharing!");
```

#### Story
```java
// Write your program here
System.out.println("I will tell you a story, but I need some information first.");
System.out.println("What is the main character called?");
String name = scanner.nextLine();
System.out.println("What is their job?");
String job = scanner.nextLine();

System.out.println("Here is the story:");
System.out.println("Once upon a time there was " + name + ", who was " + job + ".");
System.out.println("On the way to work, " + name + " relected on life.");
System.out.println("Perhaps " + name + " will not be " + job + " forever.");
```

#### Various Variables

???


#### Integer Input
```java
// Write your program here
System.out.println("Give a number:");
int givenNumber = Integer.parseInt(scanner.nextLine());
System.out.println("You gave the number " + givenNumber);   
```

#### Double Input
``` java
// Write your program here
System.out.println("Give a number:");
float givenNumber = scanner.nextFloat();
System.out.println("You gave the number " + givenNumber);
```

#### Boolean Input
```java
// Write your program here
System.out.println("Write something:");
String input = scanner.nextLine();
boolean outcome = Boolean.valueOf(input);
System.out.println("True or false? " + outcome);
```

#### Different Types of Input
```java
// Write your program here
System.out.println("Give a string:");
String inputString = scanner.nextLine();
System.out.println("Give an integer:");
int inputInt = scanner.nextInt();
System.out.println("Give a double:");
double inputDouble = scanner.nextDouble();
System.out.println("Give a boolean:");
boolean inputBool = scanner.nextBoolean();

System.out.println("You gave the string " + inputString);
System.out.println("You gave the integer " + inputInt);
System.out.println("You gave the double " + inputDouble);
System.out.println("You gave the boolean " + inputBool);
```

#### Seconds in a Day
```java
// Write your program here
System.out.println("How many days would you like to convert to seconds?");
int days = scanner.nextInt();
int hours = days * 24;
int minutes = hours * 60;
int seconds =  minutes * 60;
System.out.println(seconds);
```

#### Sum of Two Numbers
```java
// Write your program here
System.out.println("Give the first number: ");
int a = scanner.nextInt();
System.out.println("Give the second number: ");
int b = scanner.nextInt();
int c = a + b;
System.out.println("The sum of the numbers is " + c);
```
#### Sum of Three Numbers
```java
// Write your program here
System.out.println("Give the first number:");
int a = scanner.nextInt();
System.out.println("Give the second number:");
int b = scanner.nextInt();
System.out.println("Give the third number:");
int c = scanner.nextInt();
System.out.println("The sum of the numbers is " + (a + b + c));
```
#### Addition Formula
```java
// Write your program here
System.out.println("Give the first number:");
int a = scanner.nextInt();
System.out.println("Give the second number:");
int b = scanner.nextInt();
int c = a + b;
System.out.println(a + " + " + b + " = " + c);
```
#### Multiplication Formula
```java
// Write your program here
System.out.println("Give the first number:");
int a = scanner.nextInt();
System.out.println("Give the second number:");
int b = scanner.nextInt();
int c = a * b;
System.out.println(a + " * " + b + " = " + c);
```

#### Average of Two Numbers
```java
// Write your program here
System.out.println("Give the first number:");
int a = scanner.nextInt();
System.out.println("Give the second number:");
int b = scanner.nextInt();
double c = (a + b) / 2.0;
System.out.println("The average is " + c);
```
#### Average of Three Numbers
```java
// Write your program here
System.out.println("Give the first number:");
int a = scanner.nextInt();
System.out.println("Give the second number:");
int b = scanner.nextInt();
System.out.println("Give the third number:");
int c = scanner.nextInt();
double x = (a + b + c) / 3.0;
System.out.println("The average is " + x);
```

#### Simple Calculator
```java
// Write your program here
System.out.println("Give the first number:");
int a = scanner.nextInt();
System.out.println("Give the second number:");
int b = scanner.nextInt();
System.out.println(a + " + " + b + " = " + (a + b));
System.out.println(a + " - " + b + " = " + (a - b));
System.out.println(a + " * " + b + " = " + (a * b));
System.out.println(a + " / " + b + " = " + (a / (double)b));
```

#### Orwell
```java
// Write your program here
System.out.println("Give a number:");
int number = scanner.nextInt();
if (number == 1984) {
    System.out.println("Orwell");
}
```
#### Ancient
```java
// Write your program here
System.out.println("Give a year:");
int year = scanner.nextInt();
    if (year < 2015) {
    System.out.println("Ancient History!");
}
```
#### Positivity
```java
// Write your program here
System.out.println("Give a number:");
int x = scanner.nextInt();
if (x > 0) {
    System.out.println("The number is positive.");
} else {
    System.out.println("The number is not positive.");
}
```

#### Adulthood
```java
// Write your program here
System.out.println("How old are you?");
int age = scanner.nextInt();
if (age < 18) {
    System.out.println("You are not an adult");
} else {
    System.out.println("You are an adult");
}
```

#### Larger Than or Equal To
```java
// Write your program here
System.out.println("Give the first number:");
int a = scanner.nextInt();
System.out.println("Give the second number:");
int b = scanner.nextInt();
if (a > b) {
    System.out.println("Greater number is : " + a);
} else if (b > a) {
    System.out.println("Greater number is : " + b);
} else {
    System.out.println("The numbers are equal!");
}
```
