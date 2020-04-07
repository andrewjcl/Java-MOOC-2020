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
