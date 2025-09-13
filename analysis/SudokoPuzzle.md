**Problem : Sudoku Solver (Backtracking)**

Time Complexity Analysis : 
The runtime grows rapidly as the number of empty cells increases. With 20–30 blanks, puzzles are solved quickly, but beyond 40 blanks, the runtime spikes sharply, confirming the exponential nature of backtracking (**O(9^k)**, where k is the number of blanks).

---

Space Complexity Analysis : 
Memory usage grows linearly with recursion depth, which increases with the number of blanks. Although the footprint is small (a few KB), it reflects the **O(k)** stack requirement.

---

Time vs Blanks Analysis : 
The time vs empty cells plot illustrates the exponential difficulty: more blanks mean more branching in the search tree. This validates why Sudoku solvers handle typical puzzles easily but struggle with sparse grids.
