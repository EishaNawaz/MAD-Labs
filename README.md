# 📱 MAD-Labs  
## Mobile Application Development using Flutter

This repository contains all lab work for the **Mobile Application Development** course.  
It focuses on Dart fundamentals required before building Flutter applications.

![Dart](https://img.shields.io/badge/Language-Dart-blue.svg)
![Flutter](https://img.shields.io/badge/Framework-Flutter-02569B.svg)
![Status](https://img.shields.io/badge/Labs-Completed-success.svg)
![Level](https://img.shields.io/badge/Level-Beginner--to--Intermediate-orange.svg)

---

# 🧪 Lab 02 — Implement Dart Basics


This lab contains beginner-level Dart programming exercises designed to build problem-solving skills, logic development, and familiarity with user input, lists, loops, functions, and random number generation.

## 🛠 Requirements
- Dart SDK installed
- Any Dart IDE or editor (VS Code recommended)

## 📘 Exercise List

### Exercise 1 – Age to 100
Create a program that asks the user for their name and age, then tells them how many years remain until they turn 100.

### Exercise 2 – Even or Odd
Ask the user for a number and print whether it is even or odd.

### Exercise 3 – Elements Less Than 5
Given a list  
`a = [1,1,2,3,5,8,13,21,34,55,89]`  
print all elements less than 5.

### Exercise 4 – Divisors of a Number
Ask the user for a number and print all of its divisors.

### Exercise 5 – Common Elements of Two Lists
Given two lists, return a new list containing only common elements **without duplicates**, regardless of list sizes.

### Exercise 6 – Palindrome Checker
Ask the user for a string and check whether it reads the same forwards and backwards.

### Exercise 7 – Even Numbers from List
Given  
`a = [1,4,9,16,25,36,49,64,81,100]`  
create a Dart program that generates a new list containing only the even elements.

### Exercise 8 – Rock-Paper-Scissors Game
Create a two-player Rock-Paper-Scissors game against the computer.  
Take user input, compare with computer choice, and print the winner.

### Exercise 9 – Number Guessing Game
Generate a random number between 1 and 100.  
Ask the user to guess until correct and display whether guesses are too high or too low.  
Track total guesses taken.

### Exercise 10 – Prime Number Function
Create a function that checks whether a given number is prime.

### Exercise 11 – Remove Duplicates from List
Write a function that takes a list and returns a new list without duplicate elements.

### Exercise 12 – Password Generator
Create a password generator in Dart:
- Strong passwords include uppercase, lowercase, numbers, and symbols.
- Generate a new random password each time.
- Ask the user how strong they want their password (weak, medium, strong).
- Implement run-time code in the `main()` method.

### Exercise 13 – Cows and Bulls Game
The program:
1. Generates a random 4-digit number.
2. User guesses the number.
3. Correct digit in correct place → **Cow**
4. Correct digit in wrong place → **Bull**
5. Game ends when guessed correctly.
6. Display total guesses.

### Exercise 14 – Draw Game Board
Time for some fake graphics! Let’s say we want to draw game boards that look like this:

|   |   |   |
|---|---|---|
|   |   |   |
|   |   |   |

This one is 3x3 (like in tic tac toe).
Ask the user what size game board they want to draw, and draw it for them to the screen using Dart’s `print()` statement.

### Exercise 15 – Computer Guesses Your Number
User thinks of a number between 0 and 100.  
The program guesses and the user responds:
- Too high
- Too low
- Correct  
Display total guesses taken by the computer.

### Exercise 16 – Birthday Dictionary
For this exercise, we will keep track of when our friend’s birthdays are, and be able to find that information based on their name.
Create a dictionary (in your file) of names and birthdays. When you run your program it should ask the user to enter a name, and return the birthday of that person back to them. The interaction should look something like this:
> Welcome to the birthday dictionary. We know the birthdays of:
Albert Einstein
Benjamin Franklin
Ada Lovelace

> Who's birthday do you want to look up?
Benjamin Franklin

> Benjamin Franklin's birthday is 01/17/1706
