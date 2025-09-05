## 1. Time Complexity

The plot compares the execution times of **Iterative** and **Recursive** Fibonacci implementations for increasing values of `n`.  

We observe that the **Recursive approach** quickly becomes inefficient as `n` grows, since it recalculates overlapping subproblems. Its execution time grows **exponentially (O(2^n))**, making it impractical for larger inputs.  

In contrast, the **Iterative approach** computes Fibonacci numbers in a linear pass, scaling with **O(n)**. Even for very large values of `n`, it remains efficient and stable, as seen in the plot.

### Time Complexity Table
| Implementation | Best Case | Average Case | Worst Case | Performance in Plot |
|----------------|-----------|--------------|------------|----------------------|
| **Recursive Fibonacci** | O(2^n) | O(2^n) | O(2^n) | Grows exponentially, fails quickly for larger `n`. |
| **Iterative Fibonacci** | O(n) | O(n) | O(n) | Scales linearly, efficient for very large inputs. |

---

## 2. Space Complexity

The second plot compares the space requirements of both approaches.  

- **Recursive Fibonacci** requires **O(n)** stack space due to recursive function calls. As `n` increases, this stack overhead makes it less memory efficient.  
- **Iterative Fibonacci** only needs a constant number of variables to compute the sequence, resulting in **O(1) space complexity** regardless of input size.  

Thus, while recursion may be elegant, iteration is far more space-efficient and practical for large values of `n`.

### Space Complexity Table
| Implementation | Auxiliary Space | Notes |
|----------------|-----------------|-------|
| **Recursive Fibonacci** | O(n) | Stack frames grow linearly with `n`. |
| **Iterative Fibonacci** | O(1) | Uses only a few variables. |

---

## 🔎 Conclusion

- **Recursive Fibonacci** is elegant but inefficient in both **time (O(2^n))** and **space (O(n))**.  
- **Iterative Fibonacci** is highly efficient with **O(n) time** and **O(1) space**, making it the preferred choice for large inputs.  
- **Key takeaway**: Iteration wins in both **execution speed** and **memory usage**.
