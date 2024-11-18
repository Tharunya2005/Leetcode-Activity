# LeetCode Problem Solutions

This repository contains solutions to 5 LeetCode problems. Each problem is solved in Ruby, and the solutions are designed to be efficient and easy to understand.

## Problems Solved

### 1. [Add Binary](https://leetcode.com/problems/add-binary/description/)
**Problem:** Given two binary strings `a` and `b`, return their sum as a binary string.

**Solution:** The problem is solved by simulating the binary addition process. The algorithm uses two pointers to traverse the binary strings from right to left, keeping track of the carry and constructing the binary sum step by step.

**Time Complexity:** O(n), where n is the length of the longest input string.  
**Space Complexity:** O(1) (ignoring the output string).

**LeetCode Submission:** [View Submission](https://leetcode.com/submissions/detail/your_submission_id/) (Replace `your_submission_id` with the actual submission ID when available)

---

### 2. [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/description/)
**Problem:** Given a sorted array `nums`, remove the duplicates in-place such that each unique element appears only once. Return the number of unique elements.

**Solution:** This solution uses a two-pointer technique to remove duplicates. The first pointer tracks the position where the next unique element should be placed, while the second pointer traverses through the array.

**Time Complexity:** O(n), where n is the length of the array.  
**Space Complexity:** O(1) (in-place modification of the array).

**LeetCode Submission:** [View Submission](https://leetcode.com/submissions/detail/your_submission_id/) (Replace `your_submission_id` with the actual submission ID when available)

---

### 3. [Find the Index of the First Occurrence in a String](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/description/)
**Problem:** Given two strings `haystack` and `needle`, return the index of the first occurrence of `needle` in `haystack`, or `-1` if `needle` is not part of `haystack`.

**Solution:** This problem is solved using a simple search algorithm. It compares each substring of `haystack` with `needle`, returning the index of the first match. The solution can be optimized using the Knuth-Morris-Pratt (KMP) algorithm, though a simple brute force solution is sufficient for this problem.

**Time Complexity:** O(n * m), where n is the length of `haystack` and m is the length of `needle`.  
**Space Complexity:** O(1) (ignoring input strings).

**LeetCode Submission:** [View Submission](https://leetcode.com/submissions/detail/your_submission_id/) (Replace `your_submission_id` with the actual submission ID when available)

---

### 4. [Length of Last Word](https://leetcode.com/problems/length-of-last-word/description/)
**Problem:** Given a string `s` consisting of words and spaces, return the length of the last word in the string.

**Solution:** The solution involves trimming any trailing spaces and then finding the length of the last word. This can be achieved by iterating over the string from the end until we encounter a space or the beginning of the string.

**Time Complexity:** O(n), where n is the length of the string.  
**Space Complexity:** O(1) (in-place traversal).

**LeetCode Submission:** [View Submission](https://leetcode.com/submissions/detail/your_submission_id/) (Replace `your_submission_id` with the actual submission ID when available)

---

### 5. [Counter](https://leetcode.com/problems/counter/description/)
**Problem:** Create a function that returns a counter that initially returns a specified value `n` and increments the value by 1 on each subsequent call.

**Solution:** This problem is solved using closures in JavaScript. The counter function is designed to return the current value and increment it with each call.

**Time Complexity:** O(1) per call.  
**Space Complexity:** O(1) for the counter function.

**LeetCode Submission:** [View Submission](https://leetcode.com/submissions/detail/your_submission_id/) (Replace `your_submission_id` with the actual submission ID when available)

---

## Getting Started

To run the solutions:

1. **Clone the repository** to your local machine using:
    ```bash
    git clone https://github.com/your-username/leetcode-solutions.git
    ```

2. Navigate to the appropriate folder for each problem and open the solution in your preferred editor.

3. For each problem, run the code by executing the script in your Ruby environment or using your LeetCode platform to test the solution.

---

## Conclusion

These solutions provide efficient algorithms to solve common problems encountered on LeetCode. They utilize fundamental techniques such as two-pointer methods, string matching algorithms, and closures in JavaScript. The goal of this repository is to provide clear and simple solutions that can be used as a reference for learning and improving problem-solving skills.

---

**Happy Coding!**

---

### Note:
- **How to find your submission ID on LeetCode:**
  After submitting your solution, go to the **"Submissions"** tab on the problem page (e.g., for the [Add Binary problem](https://leetcode.com/problems/add-binary/description/)). Your submission ID will be available under the **"Submissions"** section, usually next to the status (Accepted/Failed). You can copy the submission URL directly from the page.
