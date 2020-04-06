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
````

#### Conversation
```java
// Write your program here
System.out.println("Greeting! How are you doing?");
String firstAnswer = scanner.nextLine();
System.out.println("Oh, how interesting. Tell me more!");
String secondAnsert = scanner.nextLine();
System.out.println("Thanks for sharing!");
````

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
````

#### Various Variables

???


#### Integer Input
````java
// Write your program here
System.out.println("Give a number:");
int givenNumber = scanner.nextInt();
System.out.println("You gave the number " + givenNumber);
```

