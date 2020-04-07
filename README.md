# Exercises for the Helsinki Java MOOC 2020 version

#### Number of Numbers
```java
// Write your program here
int count = 0;
while(true) {
    System.out.println("Give a number:");
    int number = Integer.parseInt(scanner.nextLine());
    if (number == 0) {
        break;
    } else {
        count++;
    }
}
System.out.println("Number of numbers: " + count);
```

#### Number of Negative Numbers
```java
// Write your program here
int count = 0;
while(true) {
    System.out.println("Give a number:");
    int number = Integer.parseInt(scanner.nextLine());
    if (number == 0) {
        break;
    } else if (number < 0) {
        count++;
    } else {
        // Do nothing
    }
}
System.out.println("Number of numbers: " + count);
```

#### Sum of Numbers
```java
// Write your program here
int total = 0;
while(true) {
    System.out.println("Give a number:");
    int number = Integer.parseInt(scanner.nextLine());
    if (number == 0) {
        break;
    } else {
        total += number;
    }
}
System.out.println("Sum of the numbers: " + total);
```

#### Number and Sum of Numbers
```java
// Write your program here
int total = 0;
int count = 0;
while(true) {
    System.out.println("Give a number:");
    int number = Integer.parseInt(scanner.nextLine());
    if (number == 0) {
        break;
    } else {
        total += number;
        count++;
    }
}
System.out.println("Number of numbers: " + count);
System.out.println("Sum of the numbers: " + total);
```

#### Average of Numbers
```java
// Write your program here
int total = 0;
int count = 0;
while(true) {
    System.out.println("Give a number:");
    int number = Integer.parseInt(scanner.nextLine());
    if (number == 0) {
        break;
    } else {
        total += number;
        count++;
    }
}
System.out.println("Average of the numbers: " + total / (double)count);
```

