# Day33-50-days-coding-challenge


## 🚀 Problems Covered

### 🌳 1. Binary Tree Right Side View

**Problem:**  

Given the root of a binary tree, return the nodes visible from the right side, from top to bottom.

**Approach:**  
- Perform level-order traversal (BFS) and at each level, capture the last node (rightmost).
- Collect and return the values.

**Example:**  
- Input: `[1,2,3,null,5,null,4]`  
- Output: `[1,3,4]`

**Complexity:**  
- Time: O(n), Space: O(n), where n is the number of nodes.

---

### 🔤 2. Lexicographically Smallest Palindrome
**Problem:**  

Given a string `s`, convert it into the **lexicographically smallest palindrome** with the **minimum number of operations** (character replacements).

**Approach:**  

- Use two pointers (`i`, `j`), comparing characters from both ends.
- If `s[i] != s[j]`, replace the larger character with the smaller one.
- Repeat until a palindrome is formed.
- This ensures minimum operations and smallest lexicographic order.

**Example:**  

- Input: `"egcfe"`  
- Output: `"efcfe"`  
- Input: `"abcd"`  
- Output: `"abba"`

**Complexity:**  

- Time: O(n), Space: O(n)

---

## 🔥 Key Takeaways
- Learn **Breadth-First Search (BFS)** for tree traversal.
- Master **greedy string manipulation** for palindrome construction.
- Practice both **tree data structures** and **string algorithms**.
