## 1. Time Complexity 

The plot  compares the execution times of **Linear Search** and **Binary Search** for input sizes up to 50,000.  

We observe that **Linear Search** (red curve) increases **linearly** with input size, validating its O(n) complexity. For very large arrays, this makes it inefficient.  

In contrast, **Binary Search** (blue curve) grows very slowly and almost appears flat, showing its O(log n) performance. This makes binary search far more scalable, but it requires the array to be **sorted**.  

### Time Complexity Table
| Algorithm        | Best Case | Average Case | Worst Case | Performance in Plot |
|------------------|-----------|--------------|------------|----------------------|
| **Linear Search** | O(1)     | O(n)         | O(n)       | Execution time grows linearly, inefficient for large n. |
| **Binary Search** | O(1)     | O(log n)     | O(log n)   | Execution time grows very slowly, much faster than linear search. |

---

## 2. Space Complexity

The space complexity plot shows that **both algorithms use O(1) auxiliary space** in their iterative versions. Binary Search (recursive implementation) may require O(log n) due to recursion stack, but in practice the iterative version is preferred for efficiency.  

Thus, both are space-efficient, but binary search is **significantly faster in time** for large inputs.

### Space Complexity Table
| Algorithm        | Auxiliary Space | Notes |
|------------------|-----------------|-------|
| **Linear Search** | O(1)           | Scans sequentially, no extra memory. |
| **Binary Search** | O(1) iterative / O(log n) recursive | Requires sorted input. Iterative is more space-efficient. |

---

## ✅ Conclusion

- **For small or unsorted datasets**: Linear Search works since sorting is not required.  
- **For large and sorted datasets**: Binary Search is the clear winner, with excellent scalability.  
- **Best practical choice**: Binary Search (iterative).  
