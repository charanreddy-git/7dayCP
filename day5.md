
# Day 5: Bit Manipulation

## 📖 Definition  
**Bit Manipulation** refers to algorithms and operations that directly handle the binary bits of numbers using bitwise operators (`&`, `|`, `^`, `~`, `<<`, `>>`). These tricks can yield O(1) solutions for common tasks like counting bits, toggling flags, or generating subsets.

---

## 🚀 Why Use Bit Manipulation?
- **Speed**: Single-instruction, constant-time operations on the CPU’s bit-level instructions.
- **Memory Efficiency**: Pack multiple boolean states in one integer.
- **Elegant Code**: Replace loops with masks for parity, subsets, and toggles.

---

## 🎥 Lecture & Tutorial Videos
- [ ] **Lecture: Bitwise Operators & Techniques** – https://www.youtube.com/watch?v=3v6EiZXt48o
- [ ] **Practice Demo** – https://youtu.be/eOsRzc0jQT0
- [ ] **Striver’s Playlist** – https://www.youtube.com/playlist?list=PLgUwDviBIf0rnqh8QsJaHyIX7KUiaPUv7

---

## 🔥 Codeforces Practice Set
| Link                                                       |
|------------------------------------------------------------|
| https://codeforces.com/problemset/problem/1915/A           |
| https://codeforces.com/problemset/problem/1915/B           |
| https://codeforces.com/problemset/problem/1979/B           |
| https://codeforces.com/problemset/problem/1944/B           |
- Tags: https://leetcode.com/tag/bit-manipulation/
- CodeChef Practice: https://www.codechef.com/practice/bit-manipulation
---

## 🔝 Top 5 Core Topics & Examples
1. **Basic Bitwise Ops**: masks, shifts, parity checks.
   - LeetCode: Single Number, Number of 1 Bits
2. **Counting Bits & Prefix Tricks**
   - LeetCode: Counting Bits, Binary Gap
3. **Subset Generation & Flags**
   - LeetCode: Subsets, TSP (Bitmask DP)
4. **Power-of-Two & Ranges**
   - LeetCode: Power of Two, Bitwise AND of Numbers Range
5. **Advanced Patterns**
   - LeetCode: Maximum XOR of Two Numbers, Count Palindromic Subsequences

---

## 📘 In-Depth Resources
- Blog: https://cp-algorithms.com/algebra/bit-manipulation.html
- GFG Bit Tricks: https://www.geeksforgeeks.org/bit-tricks/

---

## ✅ Checklist
- [ ] Understand six bitwise operators (`&`, `|`, `^`, `~`, `<<`, `>>`)
- [ ] Master bit counting (Hamming weight, parity)
- [ ] Use masks for subset generation & flags
- [ ] Solve power-of-two & range-mask problems
- [ ] Tackle Codeforces set above

---

## 💡 Tip
> “Think in bits, solve in constant time — bit manipulation is the coder’s secret weapon.”

---

## 🔔 Need Help?
Join our Discord Doubt Channel: https://discord.gg/D3jDzyAE
> contributed by [charanreddy-git](https://github.com/charanreddy-git/)

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const checkboxes = document.querySelectorAll('input[type="checkbox"]');
    checkboxes.forEach((checkbox) => {
      const isChecked = localStorage.getItem(checkbox.id) === "true";
      checkbox.checked = isChecked;
    });
    checkboxes.forEach((checkbox) => {
      checkbox.addEventListener("change", function () {
        localStorage.setItem(checkbox.id, checkbox.checked);
      });
    });
  });
</script>
