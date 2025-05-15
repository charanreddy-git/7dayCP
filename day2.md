# 🧭 Time Complexity & Math Foundations

---

## Time Complexity – Analyzing Algorithms

### Step 1: Understand Key Concepts

* **Big O, Ω, Θ** – formal definitions for upper, lower, and tight bounds.
* **Time vs. Space Complexity** – how runtime and memory grow with input size.

### 🎥 Tutorials (One-Shot Style)

* 🔗 **Big O, Ω, Θ** (YouTube): [Watch here](https://youtu.be/BgLTDT03QtU?si=pDBp_gP-8CJX5sz1)
* 🔗 **Time Complexity Simplified** (YouTube): [Watch here](https://youtu.be/FPu9Uld7W-E?si=OoljMO03zzKBCaDg)
* 🔗 **GeeksforGeeks Overview**: [Read here](https://www.geeksforgeeks.org/time-complexity-and-space-complexity/)

### 🛠️ Step 2: Practice Analysis

* <input type="checkbox" id="tc-task1"> Solve time-complexity practice problems on GFG
  ▶️ [GFG Practice](https://www.geeksforgeeks.org/practice-questions-time-complexity-analysis/)

### Checklist

* <input type="checkbox" id="tc-check1"> Watched both YouTube tutorials<br>
* <input type="checkbox" id="tc-check2"> Read the GeeksforGeeks article<br>
* <input type="checkbox" id="tc-check3"> Completed at least 5 GFG practice problems

---

## Math Foundations – Number Theory Basics

### 📖 Step 1: Grasp Core Topics

* **Divisibility & Primes**
* **GCD, LCM & Modular Arithmetic**
* **Basic Proof Techniques**

### 🎥 & 📚 Tutorials

* 🔗 **Intro to Number Theory** (YouTube): [Watch here](https://www.youtube.com/watch?v=1xNbjMdbjug)
* 🔗 **HackerEarth Tutorial**: [Read here](https://www.hackerearth.com/practice/math/number-theory/basic-number-theory-1/tutorial/)

### 🛠️ Step 2: Practice Problems

* <input type="checkbox" id="math-task1"> Solve "Number Groups" on HackerRank
  ▶️ [HackerRank](https://www.hackerrank.com/challenges/number-groups/problem?isFullScreen=true)<br>
* <input type="checkbox" id="math-task2"> Solve Codeforces Group problems A–D:<br>

  * A: <a href="https://codeforces.com/group/MWSDmqGsZm/contest/223338/problem/A">Problem A</a><br>
  * B: <a href="https://codeforces.com/group/MWSDmqGsZm/contest/223338/problem/B">Problem B</a><br>
  * C: <a href="https://codeforces.com/group/MWSDmqGsZm/contest/223338/problem/C">Problem C</a><br>
  * D: <a href="https://codeforces.com/group/MWSDmqGsZm/contest/223338/problem/D">Problem D</a>

### Checklist

* <input type="checkbox" id="math-check1"> Watched YouTube intro & read HackerEarth<br>
* <input type="checkbox" id="math-check2"> Completed HackerRank problem<br>
* <input type="checkbox" id="math-check3"> Solved all 4 Codeforces problems

---

## 🌟 Day 3+: More Practice & Deep Dives

* 🚀 **Complete Problem Sheet**: [Codeforces Full Set](https://codeforces.com/group/MWSDmqGsZm/contest/223338)
* 🧠 Tackle harder variants, compare different solutions, and optimize.

## 🔔 Need Help?

Join our **Discord Doubt Channel** anytime if you get stuck—we’re here to mentor you step-by-step!

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const boxes = document.querySelectorAll('input[type="checkbox"]');
    boxes.forEach(b => {
      const saved = localStorage.getItem(b.id) === "true";
      b.checked = saved;
    });
    boxes.forEach(b => {
      b.addEventListener('change', () => {
        localStorage.setItem(b.id, b.checked);
      });
    });
  });
</script>
