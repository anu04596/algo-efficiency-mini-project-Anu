**Problem : Maximizing Profit with Limited Budget (Dynamic Programming – Knapsack)**

Time Complexity Analysis : 
Execution time rises steadily as the number of items increases, consistent with the theoretical **O(n·W)** complexity. For small to medium problem sizes, the runtime remains practical, but for larger budgets (W), performance may degrade.

---

Space Complexity Analysis : 
Memory usage grows proportionally with the DP table size **(O(n·W))**, which can become a bottleneck for large capacities. For smaller inputs, memory usage is manageable, but space-optimized implementations can reduce the cost to O(W).

---

Budget vs Profit Analysis : 
The maximum profit increases with the number of items (and corresponding budget capacity). The nearly linear growth demonstrates the DP approach’s effectiveness in selecting the most profitable subset while respecting budget constraints.
