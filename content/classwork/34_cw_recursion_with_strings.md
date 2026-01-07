---
title: CW 34 - More Recursion with Strings
due_date: 2026-01-07
---

## Recursion with Strings

Implement the following methods and save them here: `.../APCSA1/apcsa-assignments-fall-YourUsername/classwork/01_07_recursion_with_strings/Strings.java`

### Print Characters

Print each character of the string.

What String method/s do you need?

What is the base case?

What is the recursive case?

Hint: It can be solved using the head-and-tail algorithm (related to the strategy we learned yesterday), which consists of two parts:
  - printing the head of the string (first character), and,
  - recursively printing its tail (the rest of characters).


```
public static void printString(String word){

}
```

---

### Print the string backwards

What String method/s do you need?

What is the base case?

What is the recursive case?

```
public static void printReverse(String word){

}
```

---


### Counting Characters in a String

Suppose you are writing an encryption program and you need to count the frequencies of the letters of the alphabet. Let’s write a recursive method for this task.

This method will have two parameters:

- word: string that will be processed
- ch: char to store the target character (the one we want to count).

The method should return an int, representing the number of occurrences of the target character in the string:

What String method/s do you need?

What is the base case?

What is the recursive case?

```
public static int countChar(String word, char ch) {

}

```

---
