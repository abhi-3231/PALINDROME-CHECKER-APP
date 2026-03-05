# Use Case 11 – Object-Oriented Palindrome Service

## Description

This use case demonstrates palindrome validation using **object-oriented design**.

The palindrome logic is separated into a **service class**, improving code organization and maintainability.

## Design Concept

Two classes are used:

1. **UseCase11PalindromeCheckerApp**
    - Contains the main method
    - Handles program execution

2. **PalindromeService**
    - Contains the palindrome checking logic
    - Reusable across other programs

## Algorithm

1. Set two pointers:
    - start = beginning
    - end = last character

2. Compare characters while moving inward

3. If mismatch occurs → not a palindrome

4. If all match → palindrome

