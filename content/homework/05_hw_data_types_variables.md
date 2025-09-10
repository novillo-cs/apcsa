---
title: HW 05 - Data Types and Variables
due_date: 2025-09-11
---

# Data Types and Variables

**Directions:** Create a new folder named `09_10_variables` inside your homework directory in your assignments repository:
`.../APCSA1/apcsa-assignments-fall-YourUsername/homework/09_10_variables`

Inside this folder, write the following programs:

1. Write a Java program (**Temperature.java**) to convert temperature from Fahrenheit to Celsius degrees. You must use variables.
   
Output:

`50.0 degrees Fahrenheit is equal to 10.0 Celsius`

2. Write a Java program (**Calculator.java**) that calculates the sum of two numbers (int or double). You must use variables.

Output:

`10 + 12 = 22`

3. Create a file **TrickyCalc.java** and copy the following code inside. Run the program. Create a file **answers.txt** or **answers.md** and respond to the following questions:
   
* What do you notice about the mySum value?
* What is the value of checkResult, and why do we get that result?

```
public class TrickyCalc{
   public static void main(String[] args){
       double mySum = 0.1 + 0.1 + 0.1;
       double tmp = 0.3;
       boolean checkResult = mySum == tmp;

       System.out.println("0.1 + 0.1 + 0.1 = " + mySum);
       System.out.println(mySum + " == " + tmp + " is " + checkResult);
   }
}
```

4. Don’t forget to add your new files to Git, then commit and push your changes. After that, go to GitHub and verify that your files are there.
I will not accept any excuses tomorrow if your homework is missing.

5. Double check that your files are organized like this in your repo:
```
apcsa-assignments-YourUsername
  classwork
    09_09_hello_world
      HelloWorld.java
  homework
    09_09_welcome
      Welcome.java
    09_10_variables
      Temperature.java
      Calculator.java
      TrickyCalc.java
      answers.txt or answers.md
```
