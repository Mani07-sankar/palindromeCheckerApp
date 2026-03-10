# Palindrome Checker App

## UC7 – Deque-Based Optimized Palindrome Checker

### Objective

The objective of this use case is to check whether a given string is a palindrome using a **Deque (Double Ended Queue)**.
Instead of reversing the string or using extra stacks, this method compares characters directly from the **front and rear** of the data structure.

---

## Concept Used

### Deque (Double Ended Queue)

A **Deque** is a data structure that allows insertion and deletion of elements from **both ends**.

Operations used in this program:

* `addLast()` – Insert character at the rear of the deque
* `removeFirst()` – Remove character from the front
* `removeLast()` – Remove character from the rear

This allows efficient comparison of characters from both ends of the string.

---

## Flow / Algorithm

1. Read a string input from the user.
2. Insert all characters of the string into a **Deque**.
3. Remove characters from the **front and rear** of the deque.
4. Compare the two characters.
5. If the characters are different → the string is **not a palindrome**.
6. If all characters match → the string is a **palindrome**.

---

## Data Structure Used

Deque (ArrayDeque implementation in Java)

---

## Time Complexity

Time Complexity: **O(n)**
Space Complexity: **O(n)**

---

## Example

Input

madam

Output

Palindrome

---

Input

hello

Output

Not Palindrome

---

## Java Concepts Used

* Java Collections Framework
* Deque Interface
* ArrayDeque Implementation
* Loops
* Conditional Statements
* Scanner for User Input



---

## Author

Developer

