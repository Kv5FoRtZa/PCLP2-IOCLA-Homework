#    Description

  This homework also has 4 tasks, but the tasks are a little bit more complicated.

#  Task 1 – Sortari (20p)

- Link the nodes in **ascending order** by updating only the `next` field.
- Return the address of the first node (head) of the sorted list.
- The array structure must NOT be modified (no swapping nodes).
- Sorting must be done **in-place**.
- Auxiliary structures are allowed.
- `n >= 1`
- Values are distinct consecutive integers starting from 1.
- Using `qsort` is not allowed.
  # Task 2 - Operatii (25p)
- get_words splits the input text s into words using delimiters: " ,.\n"
- and stores them in words.

- sort sorts the words array using qsort only:

- by word length (ascending)

- if equal length, lexicographically (strcmp-like)
#  Task 3 – KFib (20p)

Define the generalized Fibonacci sequence **KFib**:

- KFib(n) = 0, if n < K  
- KFib(n) = 1, if n = K  
- KFib(n) = KFib(n-1) + KFib(n-2) + ... + KFib(n-K), if n > K  

Indexing starts from 1.

## Requirements
- Return the n-th term of the KFib sequence.
- The result **must be computed recursively**.
- Partial points are awarded per test group.
- The result fits in 32 bits.
# Task 4 – Composite Palindrome (35p)

Given a vector of N words, find the **longest palindrome**
obtained by concatenating a **subsequence** of words.
If multiple solutions have the same length, choose the
**lexicographically smallest** one.

---

## Subtask 1 – Palindrome Check (5p)

- Return `1` if the string is a palindrome.
- Return `0` otherwise.
- No partial points.

---

##  Subtask 2 – Composite Palindrome (30p)

- Consider all valid **subsequences** of words.
- Concatenate them.
- Return:
  - The **longest palindrome** obtained.
  - If equal length → choose lexicographically smallest.
- The resulting string **must be allocated on the heap**.
