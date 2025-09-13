**Problem : Password Cracking (Brute-Force)**

Time Complexity Analysis : 
The execution time increases exponentially with password length, following **O(|charset|^L)**, where L is the password length. Even with a small charset, the time jumps significantly as length increases, demonstrating the infeasibility of brute-force for longer passwords.

---

Space Complexity Analysis : 
Memory usage remains nearly constant since guesses are generated one at a time using iterators. This matches the theoretical **O(1)** space complexity, with small overhead due to iterator management.

---

Attempts vs Length Analysis : 
The number of attempts grows exponentially with length, which the time plot mirrors. This reinforces the importance of strong passwords: even a small increase in length or charset size drastically increases brute-force difficulty.
