
[< back](README.md)

Big O notation is a way to describe the upper bound on the growth rate of an algorithm's time or space complexity as a function of the input size. It provides an asymptotic analysis of the efficiency of an algorithm. The "O" in Big O stands for "order of," and it is used to express the worst-case scenario.

1. **Time Complexity (Big O Time):**
   - **O(1):** Constant time complexity. The algorithm's execution time or number of operations remains constant regardless of the input size.
   
   - **O(log n):** Logarithmic time complexity. Common in algorithms that divide the problem into smaller subproblems.

   - **O(n):** Linear time complexity. The running time scales linearly with the size of the input.

   - **O(n log n):** Linearithmic time complexity. Often seen in efficient sorting algorithms like merge sort and heap sort.

   - **O(n^2):** Quadratic time complexity. Common in algorithms with nested iterations over the input data.

   - **O(2^n):** Exponential time complexity. Often found in algorithms that solve problems through recursive branching.

   - **O(n!):** Factorial time complexity. Extremely inefficient and usually indicates a brute-force approach.

2. **Space Complexity (Big O Space):**
   - **O(1):** Constant space complexity. The amount of memory used by the algorithm does not depend on the input size.

   - **O(n):** Linear space complexity. The amount of memory used grows linearly with the input size.

   - **O(n^2):** Quadratic space complexity. Memory usage grows with the square of the input size.

   - **O(log n):** Logarithmic space complexity. Memory usage grows logarithmically with the input size.

   - **O(n log n):** Linearithmic space complexity. Common in algorithms that use divide-and-conquer approaches.

It's important to note that Big O notation provides an upper bound and describes the worst-case scenario. It doesn't provide information about the actual running time or space usage in specific cases but gives an idea of how the algorithm's efficiency will scale as the input size increases.

[< back](README.md)