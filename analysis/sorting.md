## 1. Time Complexity 

The plot  compares the execution times of different sorting algorithms for input sizes ranging from 100 to 1200.  

We observe that **Bubble Sort** performs the worst, with its execution time increasing rapidly as input size grows due to its quadratic complexity. **Selection Sort** and **Insertion Sort** also exhibit quadratic growth, but insertion sort is slightly faster for smaller inputs.  

On the other hand, **Merge Sort** and **Quick Sort** scale much better. Merge Sort remains consistent at O(n log n), while Quick Sort also shows near O(n log n) performance in most cases, making them more suitable for larger datasets.

### Time Complexity Table
| Algorithm       | Best Case | Average Case | Worst Case | Performance in Plot |
|-----------------|-----------|--------------|------------|----------------------|
| **Bubble Sort** | O(n)      | O(n²)        | O(n²)      | Increases rapidly, worst among all. |
| **Selection Sort** | O(n²) | O(n²)        | O(n²)      | Slower than insertion sort for small n. |
| **Insertion Sort** | O(n)  | O(n²)        | O(n²)      | Performs better than bubble & selection. |
| **Merge Sort**  | O(n log n) | O(n log n)  | O(n log n) | Consistently efficient. |
| **Quick Sort**  | O(n log n) | O(n log n) | O(n²)      | Very efficient, close to merge sort. |

---

## 2. Space Complexity 

The space complexity plot shows that **Bubble, Selection, and Insertion Sorts** all use **O(1) extra space**, as they are in-place algorithms. **Quick Sort** requires O(log n) space due to recursion depth, while **Merge Sort** requires O(n) extra memory for merging, making it more memory intensive.  

Thus, while Merge Sort is fast, its memory usage is a tradeoff. Quick Sort balances both space and time well in most practical scenarios.

### Space Complexity Table
| Algorithm       | Auxiliary Space | Notes |
|-----------------|-----------------|-------|
| **Bubble Sort** | O(1)            | In-place sorting. |
| **Selection Sort** | O(1)         | In-place sorting. |
| **Insertion Sort** | O(1)         | In-place sorting. |
| **Merge Sort**  | O(n)            | Requires extra space for merging. |
| **Quick Sort**  | O(log n)        | Depends on recursion depth. |

---

## 🔎 Conclusion

- **For small datasets**: Insertion Sort is the best choice.  
- **For large datasets (guaranteed performance)**: Merge Sort.  
- **For practical average-case performance**: Quick Sort.  
- **Worst performer overall**: Bubble Sort.  
