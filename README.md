# 📘 24 Days of JavaScript – Complete Question Bank

A **structured JavaScript problem set** intended for:

* Interview preparation
* Data structures & algorithms practice
* Strengthening JavaScript fundamentals

---

## 📌 General Instructions

1. Solve each problem using **JavaScript (ES6+)**
2. Do not use external libraries unless mentioned
3. Input and output formats must be followed exactly
4. Time and space efficiency should be considered where applicable
5. Write clean and readable code

---

## 🗓 Day 1 – Strings & Arrays (Fundamentals)

### 1. Remove duplicate characters from a string

**Description:**
Given a string, remove all duplicate characters while keeping the first occurrence order intact.

**Input:**
`"programming"`

**Output:**
`"progamin"`

---

### 2. Remove duplicate elements from an array and count occurrences

**Description:**
Given an array of numbers, return:

* an array of unique elements
* an object representing the frequency of each element

**Input:**
`[1, 2, 2, 3, 3, 3]`

**Output:**

```js
{
  unique: [1, 2, 3],
  count: { 1: 1, 2: 2, 3: 3 }
}
```

---

### 3. Remove duplicate elements using `filter`

**Description:**
Remove duplicate values from an array using the `filter` method.

**Input:**
`[1, 2, 2, 3, 4, 4]`

**Output:**
`[1, 2, 3, 4]`

---

### 4. Reverse a string without reversing individual words

**Description:**
Reverse the order of words in a sentence without changing the letters inside each word.

**Input:**
`"Hello World From JavaScript"`

**Output:**
`"JavaScript From World Hello"`

---

## 🗓 Day 2 – Basic Algorithms

### 5. Reverse a string with individual words reversed

**Description:**
Reverse the entire string including characters of each word.

**Input:**
`"Hello World"`

**Output:**
`"dlroW olleH"`

---

### 6. Reverse a string without using built-in reverse methods

**Description:**
Reverse a string without using `split()`, `reverse()`, or `join()`.

**Input:**
`"abcd"`

**Output:**
`"dcba"`

---

### 7. Find factorial of a number

**Description:**
Calculate the factorial of a given non-negative integer.

**Input:**
`5`

**Output:**
`120`

---

### 8. Check if two strings are anagrams

**Description:**
Determine whether two strings contain the same characters in the same frequency.

**Input:**
`"listen", "silent"`

**Output:**
`true`

---

### 9. Swap two numbers using a third variable

**Input:**
`a = 5, b = 10`

**Output:**
`a = 10, b = 5`

---

### 10. Swap two numbers without using a third variable

**Input:**
`a = 7, b = 3`

**Output:**
`a = 3, b = 7`

---

## 🗓 Day 3 – Palindrome & Word Problems

### 11. Check if a string or number is a palindrome using reverse

**Input:**
`"madam"`

**Output:**
`true`

---

### 12. Check if a string or number is a palindrome without reverse

**Input:**
`121`

**Output:**
`true`

---

### 13. Find the longest word in a sentence

**Description:**
Return the longest word from a sentence.

**Input:**
`"JavaScript is extremely powerful"`

**Output:**
`"extremely"`

---

## 🗓 Day 4 – String Analysis

### 14. Find the longest common prefix from an array of strings

**Input:**
`["flower", "flow", "flight"]`

**Output:**
`"fl"`

---

### 15. Count vowels and their occurrences

**Input:**
`"education"`

**Output:**

```js
{ a: 1, e: 2, i: 1, o: 1, u: 1 }
```

---

### 16. Count character frequency in a string

**Input:**
`"aabbbc"`

**Output:**

```js
{ a: 2, b: 3, c: 1 }
```

---

## 🗓 Day 5 – Array Pair Problems

### 17. Find the first pair whose sum is zero

**Input:**
`[-3, 1, 3, 4, -1]`

**Output:**
`[-3, 3]`

---

### 18. Find all pairs whose sum is zero

**Input:**
`[-2, 2, -1, 1, 3]`

**Output:**

```js
[[-2, 2], [-1, 1]]
```

---

### 19. Find the largest pair from an unsorted array

**Input:**
`[10, 5, 20, 8]`

**Output:**
`[20, 10]`

---

## 🗓 Day 6 – Searching & Fibonacci

### 20. Find index of an element in an array

**Input:**
`[5, 8, 3, 9], 3`

**Output:**
`2`

---

### 21. Generate Fibonacci series up to N terms

**Input:**
`7`

**Output:**
`[0, 1, 1, 2, 3, 5, 8]`

---

## 🗓 Day 7 – Missing Numbers

### 22. Find the missing number in a sequence

**Input:**
`[1, 2, 4, 5]`

**Output:**
`3`

---

### 23. Find all missing numbers within a range

**Input:**
`[1, 3, 6]`

**Output:**
`[2, 4, 5]`

---

## 🗓 Day 8 – Sorting & Prime Numbers

### 24. Sort characters of a string alphabetically

**Input:**
`"dcba"`

**Output:**
`"abcd"`

---

### 25. Check if a number is prime

**Input:**
`13`

**Output:**
`true`

---

### 26. Print all numbers from 2 to 100 that are prime

**Output:**
`[2, 3, 5, 7, 11, ..., 97]`

---

## 🗓 Day 9 – Array & String Transformation

### 27. Find union of two arrays

**Input:**
`[1, 2, 3], [3, 4, 5]`

**Output:**
`[1, 2, 3, 4, 5]`

---

### 28. Find first duplicate element

**Input:**
`[1, 2, 3, 2, 4]`

**Output:**
`2`

---

### 29. FizzBuzz from 1 to 100

**Output:**

* Multiples of 3 → `"Fizz"`
* Multiples of 5 → `"Buzz"`
* Multiples of both → `"FizzBuzz"`

---

### 30. Capitalize first letter of each word

**Input:**
`"hello world"`

**Output:**
`"Hello World"`

---

## 🗓 Day 10 – 2D Arrays

### 31. Find the largest element from each row of a 2D array

**Input:**

```js
[
  [1, 2, 3],
  [4, 9, 6],
  [7, 8, 5]
]
```

**Output:**
`[3, 9, 8]`

---

## 🗓 Day 24 – Advanced Array Problem

### 32. Find all unique triplets whose sum equals a given value

**Description:**
Return all unique triplets where the sum of three numbers equals the target value.

**Input:**
`[-1, 0, 1, 2, -1, -4], 0`

**Output:**

```js
[
  [-1, -1, 2],
  [-1, 0, 1]
]
```

---

### 33. Convert an array into an object

**Input:**
`["A", "B", "C"]`

**Output:**

```js
{ 0: "A", 1: "B", 2: "C" }
```
