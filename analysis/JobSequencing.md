**Problem : TV Commercial Scheduling (Greedy Approach) - Job Sequencing**

Time Complexity Analysis : 
The execution time grows gradually with the number of ads, following the expected O(n log n + n·m) trend, where n is the number of ads and m is the maximum deadline. Even at 500 ads, the runtime remains negligible, highlighting the efficiency of the greedy strategy for large datasets.

---

Space Complexity Analysis : 
Memory usage increases linearly with the number of ads since the algorithm maintains a slot array up to the maximum deadline. This behavior confirms the O(m) theoretical complexity, with practical usage remaining very low (only a few KB).

---

Revenue vs Ads Analysis : 
The revenue increases almost linearly with the number of ads, as the greedy strategy prioritizes high-profit commercials within deadlines. In practice, the growth may flatten due to limited slots, but the algorithm is effective in maximizing revenue under constraints.
