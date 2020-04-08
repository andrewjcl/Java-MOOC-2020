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

#### Average of Positive Numbers
```java
// Write your program here
int total = 0;
int count = 0;
while(true) {
    System.out.println("Give a number:");
    int number = Integer.parseInt(scanner.nextLine());
    if (number == 0) {
        break;
    } else if (number > 0){
        total += number;
        count++;
    } else {
        // Do nothing
    }
}

if (count == 0) {
    System.out.println("Cannot calculate the average");
} else {
    System.out.println("Average of the numbers: " + total / (double)count);
}
```

#### Counting
```java
// Write your program here
int x = Integer.parseInt(scanner.nextLine());

for (int i = 0; i <= x; i++) {
    System.out.println(i);
}
```

#### Counting to 100
```java
// Write your program here
int x = Integer.parseInt(scanner.nextLine());

for (int i = x; i <= 100; i++) {
    System.out.println(i);
}
```

#### From Where to Where
```java
// Write your program here
System.out.println("Where to?");
int end = Integer.parseInt(scanner.nextLine());
System.out.println("Where from?");
int start = Integer.parseInt(scanner.nextLine());

for (int i = start; i <= end; i++) {
    System.out.println(i);
}
```

#### The Sum of a Sequence
```java
// Write your program here
System.out.println("Last number?");
int last = Integer.parseInt(scanner.nextLine());
int total = 0;
for (int i = 0; i <= last; i++) {
    total += i;
}
System.out.println("The sum is " + total);
```

#### The Sum of a Sequence (Sequel)
```java
// Write your program here
System.out.println("First number?");
int first = Integer.parseInt(scanner.nextLine());
System.out.println("Last number?");
int last = Integer.parseInt(scanner.nextLine());
int total = 0;
for (int i = first; i <= last; i++) {
    total += i;
}
System.out.println("The sum is " + total);
```
