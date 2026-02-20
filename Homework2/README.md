##  Overview
This assignment consists of four x86 Assembly tasks focused on filtering
numbers, validating and sorting structured data, implementing Base64
encoding, and building a Sudoku validator.

---

#  Task 1 – Number Filtering (15p)

### Subtask 1 – Remove Odd Numbers from the given array
- Filter out all odd values from the input array.

### Subtask 2 – Remove Powers of 2 from the given array
- From the remaining numbers, remove all values that are powers of 2.

#  Task 2 – Events (30p)

## Subtask 1 – Validate Events

- Validate all the events that fulfill this rules
### Validation Rules
- Year ∈ [1990, 2030]
- Month ∈ [1, 12]
- Day valid for the given month (February = 28 days)

## Subtask 2 – Sort Events

### Sorting Rules
1. Valid events come first.
2. If both events are valid:
   - Sort by year
   - Then month
   - Then day
3. If dates are equal:
   - Sort lexicographically by name (strcmp behavior).
4. Sorting must be done **in place**.

---

# Task 3 – Base64 Encoding (25p)

### Requirements
- Input length is always a multiple of 3.
- Process input in 3-byte blocks.
- Convert 24-bit blocks into 4 groups of 6 bits.
- Map each group to Base64 table characters.

---

#  Task 4 – Sudoku Checker (20p)


### Requirements
- Board is an 81-byte array.
- Indices range from 0 to 8.
- Each row, column, and 3x3 box must contain digits 1–9 exactly once.
- Return value in `eax`:
  - `1` → correct
  - `2` → incorrect
