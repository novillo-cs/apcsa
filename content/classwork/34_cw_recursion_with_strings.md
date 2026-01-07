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

### Number Letter Counts  

### [Project Euler - Problem 17](https://projecteuler.net/problem=17)

This problem must be solved using recursion.

If the numbers 1 to 5 are to are written out in words: one, two, three, four, five, then there are 3 + 3 + 5 + 4 + 4 = 19 letters used in total.

If all the numbers from 1 to 1000 (one thousand) inclusive were written out in words, how many letters would be used?

NOTE: Do not count spaces or hyphens. For example, 342 (three hundred and forty-two) contains 23 letters and 115 (one hundred and fifteen) contains 20 letters. The use of "and" when writing out numbers is in compliance with British usage.

### Think about the problem:

First how can you implement this method to return the number in letters:

```
public static String numberToWords(int number) {

}
```

- How can you have a reference to the numbers in words? Should these words be predefined maybe using arrays?
- How should the possible number cases be implemented?
    - Handling Hundreds: Greater than or equal to 100
    - Handling Tens: 20 to 99
    - Handling Teens: 10 to 19
    - Handling Ones:Less than 10
- How can you check the value of the number in the recursive method? How to decide whether to use the word for hundreds, tens, teens, or ones?
- What is the base case?
- What is the recursive case?
- What parameter must be sent in each recursive call?


Let's do it from 1-1000 to have the total number of letters in all those numbers:

```
Declare an integer variable 'result' to store total number of letters
for each number from 1 to 1000
	call recursive method numberToWords(number here), this return number in words
	get the length of the word returned from the recursive method and add it to 'result'
 ```
 

### Debugging and Testing:

- Debug the program by running it with small inputs.
- Test the program with a range of numbers and verify the results.

---
