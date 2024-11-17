
# LinkedList Practice Exercises in Java

This document contains eight exercises designed to help you practice problem-solving using Java's built-in `LinkedList` class. Each exercise is detailed and progressively challenging, focusing on applying the `LinkedList` class in real-world logic problems.

---

## **Exercise 1: Reverse a List**
**Description:**  
Write a program that takes a `LinkedList<Integer>` as input and reverses its elements. You are required to create a new linked list to store the reversed elements.  
- Input: A `LinkedList` of integers, e.g., [1, 2, 3, 4].  
- Output: A new `LinkedList` with reversed elements, e.g., [4, 3, 2, 1].  
- **Hint:** Use methods such as `addFirst`.

---

## **Exercise 2: Remove Every Third Element**
**Description:**  
Given a `LinkedList<String>` containing a list of items, remove every third element from the list until only a few elements remain.  
- Input: A `LinkedList` of strings, e.g., ["A", "B", "C", "D", "E", "F", "G"].  
- Output: The modified list, e.g., ["A", "B", "D", "E", "G"].  
- **Requirement:** Use the `remove` method of the `LinkedList` class.

---

## **Exercise 3: Find the Kth Element**
**Description:**  
Write a program to find the **kth element from the end** in a `LinkedList<Integer>`.  
- Input: A `LinkedList` of integers and an integer `k`, e.g., list = [10, 20, 30, 40, 50], k = 2.  
- Output: The kth element from the end, e.g., 40 for the given input.  
- **Requirement:** Use methods like `size` and `get`.

---

## **Exercise 4: Merge Two Lists**
**Description:**  
Given two sorted `LinkedList<Integer>` objects, merge them into a single sorted linked list.  
- Input: Two sorted linked lists, e.g., [1, 3, 5] and [2, 4, 6].  
- Output: A merged and sorted linked list, e.g., [1, 2, 3, 4, 5, 6].  
- **Hint:** Use the `poll` method or iterate over the lists.

---

## **Exercise 5: Check for Palindrome**
**Description:**  
Check if the elements of a `LinkedList<Character>` form a palindrome.  
- Input: A `LinkedList` of characters, e.g., ['r', 'a', 'c', 'e', 'c', 'a', 'r'].  
- Output: A boolean value, e.g., `true` for the given input.  
- **Requirement:** You can use `pollFirst` and `pollLast` methods.

---

## **Exercise 6: Rotate the List**
**Description:**  
Rotate a `LinkedList<Integer>` to the right by `k` positions.  
- Input: A `LinkedList` of integers and an integer `k`, e.g., list = [1, 2, 3, 4, 5], k = 2.  
- Output: The rotated linked list, e.g., [4, 5, 1, 2, 3].  
- **Hint:** Use `addFirst` and `removeLast` methods.

---

## **Exercise 7: Find Intersection**
**Description:**  
Given two `LinkedList<Integer>` objects, find their intersection (common elements).  
- Input: Two linked lists, e.g., [1, 2, 3, 4] and [3, 4, 5, 6].  
- Output: A new `LinkedList` containing the intersection, e.g., [3, 4].  
- **Requirement:** Use methods like `contains` and `add`.

---

## **Exercise 8: Josephus Problem**
**Description:**  
Solve the Josephus problem for `n` people using a `LinkedList<Integer>`.  
- Input: An integer `n` (number of people) and `k` (step size), e.g., n = 7, k = 3.  
- Output: The position of the last survivor, e.g., 4 for the given input.  
- **Hint:** Simulate the process by repeatedly removing elements at specific intervals.

---

**Happy Coding!**
