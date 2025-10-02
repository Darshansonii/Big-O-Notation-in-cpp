# Big-O-Notation-in-cpp

--------------------------------------------------
AIM
--------------------------------------------------
The aim of this project is to understand and demonstrate Big O Notation in C++ for analyzing the time and space complexity of algorithms.  
It helps in measuring how an algorithm’s performance grows with input size and enables selection of efficient algorithms.

--------------------------------------------------
THEORY
--------------------------------------------------
Big O Notation is a mathematical notation used to describe the upper bound of an algorithm’s runtime or memory requirement as a function of input size n.  
It focuses on the growth rate of an algorithm, ignoring constant factors and lower-order terms.  

Common Time Complexities:
1. O(1) – Constant Time: Execution time does not depend on input size.  
2. O(log n) – Logarithmic Time: Execution time grows logarithmically.  
3. O(n) – Linear Time: Execution time grows linearly with input size.  
4. O(n log n) – Linearithmic Time: Combination of linear and logarithmic growth.  
5. O(n^2) – Quadratic Time: Execution time grows proportionally to the square of input size.  
6. O(2^n) – Exponential Time: Execution time doubles with each input element.  
7. O(n!) – Factorial Time: Execution time grows factorially with input size.  

Big O is important for:
- Comparing algorithm efficiency  
- Predicting performance for large datasets  
- Optimizing time-critical programs

--------------------------------------------------
ALGORITHM
--------------------------------------------------
The algorithm part for Big O is essentially analyzing operations and estimating their growth:

1. O(1) – Constant Time Example:
Access an array element: arr[i];

2. O(n) – Linear Time Example:
for (int i = 0; i < n; i++) {
    process(arr[i]);
}

3. O(n^2) – Quadratic Time Example:
for (int i = 0; i < n; i++) {
    for (int j = 0; j < n; j++) {
        process(arr[i], arr[j]);
    }
}

4. O(log n) – Logarithmic Time Example (Binary Search):
- low = 0, high = n-1
- while low <= high:
    mid = (low + high)/2
    compare arr[mid] with target
    adjust low or high accordingly

5. O(n log n) – Linearithmic Time Example (Merge Sort):
- Divide array into halves recursively
- Merge sorted halves

Steps to Analyze Big O for any code:
1. Identify loops and nested loops  
2. Determine how many times each loop executes relative to input size n  
3. Combine operations, ignore constants and lower-order terms  
4. Express the growth rate as Big O notation

--------------------------------------------------
CONCLUSION
--------------------------------------------------
- Big O Notation is a standard way to describe algorithm efficiency.  
- It focuses on growth rate rather than exact execution time.  
- Helps in comparing, analyzing, and optimizing algorithms.  
- Understanding Big O is crucial for designing scalable and efficient C++ programs.  
- It forms the foundation for learning data structures, searching, sorting, and advanced algorithms.
