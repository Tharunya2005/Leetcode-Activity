# LeetCode Problem Solutions

This repository contains solutions to 5 LeetCode problems. Each problem is solved in Ruby, and the solutions are designed to be efficient and easy to understand.

## Problems Solved

### 1. [Add Binary](https://leetcode.com/problems/add-binary/description/)
**Problem:** Given two binary strings `a` and `b`, return their sum as a binary string.

**Concepts:**  
- **Binary Arithmetic**  
- **String Manipulation**  
- **Carry Handling in Binary Addition**

**Description:** The problem is solved by simulating the binary addition process. We use two pointers to traverse the binary strings from right to left, keeping track of the carry and constructing the binary sum step by step. As we add each corresponding pair of bits, we also handle the carry from previous additions.

**Solution Approach:**  
- Start from the rightmost bit of both strings.
- Add corresponding bits and track the carry.
- Build the result from right to left, adding each sum and carry.

**Time Complexity:** O(n), where n is the length of the longest input string.  
**Space Complexity:** O(1) (ignoring the output string).

**LeetCode Submission:** [View Submission](https://leetcode.com/submissions/detail/your_submission_id/) (Replace `your_submission_id` with the actual submission ID when available)

---

### 2. [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/description/)
**Problem:** Given a sorted array `nums`, remove the duplicates in-place such that each unique element appears only once. Return the number of unique elements.

**Concepts:**  
- **Two-pointer technique**  
- **In-place Array Manipulation**  
- **Array Optimization**

**Description:** This solution uses a two-pointer technique to remove duplicates in-place. The first pointer tracks where the next unique element should be placed, while the second pointer traverses through the array to find unique elements.

**Solution Approach:**  
- Initialize two pointers: one for the current unique element index and one for the array traversal.
- When a unique element is found, place it at the current unique index and move the unique index pointer.

**Time Complexity:** O(n), where n is the length of the array.  
**Space Complexity:** O(1) (in-place modification of the array).

**LeetCode Submission:** [View Submission](https://leetcode.com/submissions/detail/your_submission_id/) (Replace `your_submission_id` with the actual submission ID when available)

---

### 3. [Find the Index of the First Occurrence in a String](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/description/)
**Problem:** Given two strings `haystack` and `needle`, return the index of the first occurrence of `needle` in `haystack`, or `-1` if `needle` is not part of `haystack`.

**Concepts:**  
- **String Matching**  
- **Brute Force Search**  
- **Sliding Window (Optional Optimization)**

**Description:** This problem is solved using a simple brute-force search algorithm. We compare each substring of `haystack` with `needle`, returning the index of the first match. Although more efficient algorithms like the Knuth-Morris-Pratt (KMP) algorithm could be used, a brute-force solution is sufficient for this problem.

**Solution Approach:**  
- Iterate over the `haystack` and check if the substring from the current index matches the `needle`.
- If a match is found, return the index; otherwise, return -1 after checking all possible positions.

**Time Complexity:** O(n * m), where n is the length of `haystack` and m is the length of `needle`.  
**Space Complexity:** O(1) (ignoring input strings).

**LeetCode Submission:** [View Submission](https://leetcode.com/submissions/detail/your_submission_id/) (Replace `your_submission_id` with the actual submission ID when available)

---

### 4. [Length of Last Word](https://leetcode.com/problems/length-of-last-word/description/)
**Problem:** Given a string `s` consisting of words and spaces, return the length of the last word in the string.

**Concepts:**  
- **String Traversal**  
- **Space and Time Optimization**  
- **Edge Case Handling (trailing spaces)**

**Description:** This problem is solved by first trimming any trailing spaces from the string, then iterating over the string from the end to find the length of the last word. It stops when the first space is encountered or when the beginning of the string is reached.

**Solution Approach:**  
- Remove any trailing spaces from the string.
- Start from the end of the string and count characters until a space or the beginning is reached.

**Time Complexity:** O(n), where n is the length of the string.  
**Space Complexity:** O(1) (in-place traversal).

**LeetCode Submission:** [View Submission](https://leetcode.com/submissions/detail/your_submission_id/) (Replace `your_submission_id` with the actual submission ID when available)

---

### 5. [Counter](https://leetcode.com/problems/counter/description/)
**Problem:** Create a function that returns a counter that initially returns a specified value `n` and increments the value by 1 on each subsequent call.

**Concepts:**  
- **Closures**  
- **State Management**  
- **Functional Programming**  

**Description:** This problem is solved using closures. The counter function uses a closure to maintain its state (the current count), returning the current value and incrementing it on each subsequent call.

**Solution Approach:**  
- Define an outer function that initializes the counter value.
- Use a closure to maintain the current count across multiple function calls.

**Time Complexity:** O(1) per call.  
**Space Complexity:** O(1) for the counter function.

**LeetCode Submission:** [View Submission](https://leetcode.com/submissions/detail/your_submission_id/) (Replace `your_submission_id` with the actual submission ID when available)

---
