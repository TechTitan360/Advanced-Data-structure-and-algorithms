# Advanced Data Structures and Algorithms - LeetCode Solutions

## 📚 Repository Overview

This repository contains my solutions to various LeetCode problems, organized by difficulty level and topic categories. Each solution is implemented in Java and demonstrates different algorithmic techniques and data structure applications.

## 🎯 Learning Objectives

- Master fundamental and advanced data structures
- Implement various algorithmic paradigms
- Solve coding interview problems efficiently
- Analyze time and space complexity

## 📁 Repository Structure

```
├── Advanced/
│   ├── Divide and Conquer/
│   └── Dynamic Programming/
├── Intermediate/
│   ├── Binary Search/
│   ├── Bit Manipulation/
│   ├── Brainteaser/
│   ├── Greedy/
│   ├── Hash Table/
│   ├── Linked List/
│   └── Sliding Window/
└── README.md
```

## 📋 Problem Categories

### Advanced Level

#### 🔀 Divide and Conquer
| Problem | Solution | Difficulty | Time Complexity | Space Complexity |
|---------|----------|------------|----------------|------------------|
| [53. Maximum Subarray](Advanced/Divide%20and%20Conquer/Q-53.txt) | [Java](Advanced/Divide%20and%20Conquer/Q-53.txt) | Medium | O(n) | O(1) |
| [169. Majority Element](Advanced/Divide%20and%20Conquer/Q-169.txt) | [Java](Advanced/Divide%20and%20Conquer/Q-169.txt) | Easy | O(n) | O(1) |

#### 🎯 Dynamic Programming
| Problem | Solution | Difficulty | Time Complexity | Space Complexity |
|---------|----------|------------|----------------|------------------|
| [53. Maximum Subarray](Advanced/Dynamic%20Programming/Q-53.txt) | [Java](Advanced/Dynamic%20Programming/Q-53.txt) | Medium | O(n) | O(1) |
| [2327. Number of People Aware of a Secret](Advanced/Dynamic%20Programming/Q-2327.txt) | [Java](Advanced/Dynamic%20Programming/Q-2327.txt) | Medium | O(n × forget) | O(n) |

### Intermediate Level

#### 🔍 Binary Search
| Problem | Solution | Difficulty | Time Complexity | Space Complexity |
|---------|----------|------------|----------------|------------------|
| [33. Search in Rotated Sorted Array](Intermediate/Binary%20Search/Q33.txt) | [Java](Intermediate/Binary%20Search/Q33.txt) | Medium | O(log n) | O(1) |
| [81. Search in Rotated Sorted Array II](Intermediate/Binary%20Search/Q81.txt) | [Java](Intermediate/Binary%20Search/Q81.txt) | Medium | O(n) worst, O(log n) avg | O(1) |
| [153. Find Minimum in Rotated Sorted Array](Intermediate/Binary%20Search/Q153.txt) | [Java](Intermediate/Binary%20Search/Q153.txt) | Medium | O(log n) | O(1) |
| [209. Minimum Size Subarray Sum](Intermediate/Binary%20Search/Q209.txt) | [Java](Intermediate/Binary%20Search/Q209.txt) | Medium | O(n) | O(1) |
| [704. Binary Search](Intermediate/Binary%20Search/Q704.txt) | [Java](Intermediate/Binary%20Search/Q704.txt) | Easy | O(log n) | O(log n) |
| [875. Koko Eating Bananas](Intermediate/Binary%20Search/Q875.txt) | [Java](Intermediate/Binary%20Search/Q875.txt) | Medium | O(n log max) | O(1) |
| [1011. Capacity To Ship Packages Within D Days](Intermediate/Binary%20Search/Q1011.txt) | [Java](Intermediate/Binary%20Search/Q1011.txt) | Medium | O(n log sum) | O(1) |

#### 🔢 Bit Manipulation
| Problem | Solution | Difficulty | Time Complexity | Space Complexity |
|---------|----------|------------|----------------|------------------|
| [2749. Minimum Operations to Make the Integer Zero](Intermediate/Bit%20Manipulation/Q-2749.txt) | [Java](Intermediate/Bit%20Manipulation/Q-2749.txt) | Medium | O(64) = O(1) | O(1) |
| [3495. Kth Smallest Amount With Single Denomination Combination](Intermediate/Bit%20Manipulation/Q-3495.txt) | [Java](Intermediate/Bit%20Manipulation/Q-3495.txt) | Hard | O(q × log r) | O(1) |

#### 🧠 Brainteaser
| Problem | Solution | Difficulty | Time Complexity | Space Complexity |
|---------|----------|------------|----------------|------------------|
| [2396. Strictly Palindromic Number](Intermediate/Brainteaser/Q-2396.txt) | [Java](Intermediate/Brainteaser/Q-2396.txt) | Medium | O(1) | O(1) |
| [2749. Minimum Operations to Make the Integer Zero](Intermediate/Brainteaser/Q-2749.txt) | [Java](Intermediate/Brainteaser/Q-2749.txt) | Medium | O(log n) | O(1) |

#### 🎯 Greedy
| Problem | Solution | Difficulty | Time Complexity | Space Complexity |
|---------|----------|------------|----------------|------------------|
| [11. Container With Most Water](Intermediate/Greedy/Q-11.txt) | [Java](Intermediate/Greedy/Q-11.txt) | Medium | O(n) | O(1) |
| [781. Rabbits in Forest](Intermediate/Greedy/Q-781.txt) | [Java](Intermediate/Greedy/Q-781.txt) | Medium | O(n) | O(n) |
| [1733. Minimum Number of People to Teach](Intermediate/Greedy/Q-1733.txt) | [Java](Intermediate/Greedy/Q-1733.txt) | Medium | O(n × m + F) | O(n × m) |
| [1792. Maximum Average Pass Ratio](Intermediate/Greedy/Q-1792.txt) | [Java](Intermediate/Greedy/Q-1792.txt) | Medium | O(n log n + k log n) | O(n) |

#### #️⃣ Hash Table
| Problem | Solution | Difficulty | Time Complexity | Space Complexity |
|---------|----------|------------|----------------|------------------|
| [3. Longest Substring Without Repeating Characters](Intermediate/Hash%20Table/Q-3.txt) | [Java](Intermediate/Hash%20Table/Q-3.txt) | Medium | O(n) | O(min(m,n)) |
| [49. Group Anagrams](Intermediate/Hash%20Table/Q-49.txt) | [Java](Intermediate/Hash%20Table/Q-49.txt) | Medium | O(n·k log k) | O(n·k) |
| [169. Majority Element](Intermediate/Hash%20Table/Q-169.txt) | [Java](Intermediate/Hash%20Table/Q-169.txt) | Easy | O(n) | O(1) |
| [217. Contains Duplicate](Intermediate/Hash%20Table/Q-217.txt) | [Java](Intermediate/Hash%20Table/Q-217.txt) | Easy | O(n) | O(n) |
| [299. Bulls and Cows](Intermediate/Hash%20Table/Q-299.txt) | [Java](Intermediate/Hash%20Table/Q-299.txt) | Medium | O(n) | O(1) |
| [451. Sort Characters By Frequency](Intermediate/Hash%20Table/Q-451.txt) | [Java](Intermediate/Hash%20Table/Q-451.txt) | Medium | O(n log n) | O(n) |
| [781. Rabbits in Forest](Intermediate/Hash%20Table/Q-781.txt) | [Java](Intermediate/Hash%20Table/Q-781.txt) | Medium | O(n) | O(n) |

#### 🔗 Linked List
| Problem | Solution | Difficulty | Time Complexity | Space Complexity |
|---------|----------|------------|----------------|------------------|
| [206. Reverse Linked List](Intermediate/Linked%20List/Q-206.txt) | [Java](Intermediate/Linked%20List/Q-206.txt) | Easy | O(n) | O(1) |
| [237. Delete Node in a Linked List](Intermediate/Linked%20List/Q-237.txt) | [Java](Intermediate/Linked%20List/Q-237.txt) | Medium | O(1) | O(1) |
| [876. Middle of the Linked List](Intermediate/Linked%20List/Q-876.txt) | [Java](Intermediate/Linked%20List/Q-876.txt) | Easy | O(n) | O(1) |

#### 🪟 Sliding Window
| Problem | Solution | Difficulty | Time Complexity | Space Complexity |
|---------|----------|------------|----------------|------------------|
| [3. Longest Substring Without Repeating Characters](Intermediate/Sliding%20Window/Q-3.txt) | [Java](Intermediate/Sliding%20Window/Q-3.txt) | Medium | O(n) | O(min(m,n)) |
| [209. Minimum Size Subarray Sum](Intermediate/Sliding%20Window/Q209.txt) | [Java](Intermediate/Sliding%20Window/Q209.txt) | Medium | O(n) | O(1) |
| [643. Maximum Average Subarray I](Intermediate/Sliding%20Window/Q-643.txt) | [Java](Intermediate/Sliding%20Window/Q-643.txt) | Easy | O(n) | O(1) |
| [1052. Grumpy Bookstore Owner](Intermediate/Sliding%20Window/Q-1052.txt) | [Java](Intermediate/Sliding%20Window/Q-1052.txt) | Medium | O(n) | O(1) |
| [1343. Number of Sub-arrays of Size K and Average Greater than or Equal to Threshold](Intermediate/Sliding%20Window/Q-1343.txt) | [Java](Intermediate/Sliding%20Window/Q-1343.txt) | Medium | O(n) | O(1) |

## 📊 Statistics

- **Total Problems Solved**: 28
- **Easy**: 6 problems
- **Medium**: 21 problems  
- **Hard**: 1 problem
- **Language**: Java
- **Focus Areas**: Data Structures, Algorithms, Problem Solving

## 🛠️ Technologies Used

- **Programming Language**: Java
- **Development Environment**: VS Code / IntelliJ IDEA
- **Version Control**: Git & GitHub

## 📈 Problem Solving Approach

1. **Understanding**: Carefully read and analyze the problem
2. **Planning**: Identify the appropriate data structure and algorithm
3. **Implementation**: Write clean, efficient code
4. **Optimization**: Analyze time and space complexity
5. **Testing**: Verify with example test cases

## 🎓 Key Concepts Covered

- **Data Structures**: Arrays, Hash Tables, Linked Lists, Trees, Heaps
- **Algorithms**: Binary Search, Dynamic Programming, Greedy, Divide & Conquer
- **Techniques**: Two Pointers, Sliding Window, Bit Manipulation
- **Complexity Analysis**: Big O notation for time and space

## 📝 Notes

- Each solution includes the problem number and title
- Code is well-commented and follows best practices
- Solutions are optimized for both time and space complexity
- Multiple approaches are explored where applicable

## 📞 Contact

Feel free to reach out if you have any questions about the implementations or would like to discuss algorithmic approaches!

---
**Repository maintained for academic purposes - ADSA Course**