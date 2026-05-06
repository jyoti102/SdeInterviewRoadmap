# **Google L4 Software Engineer: 4-Month Accelerated Pattern-Based Roadmap**

This roadmap is tailored for a senior backend Java engineer (7+ years experience) transitioning from high-scale product work (10k QPS) to Google's L4 algorithmic standards.

### **The Strategic Framework: The 1–2–1 Rubric**
Instead of solving hundreds of random problems, you will master the **28 core patterns** using a scoring method designed for depth. For each pattern, solve:
*   **1 Easy Problem:** To build initial intuition.
*   **2 Medium Problems:** To learn the most common twists and applications.
*   **1 Hard Problem:** To master complex optimizations and layered follow-ups.
This approach ensures you can identify the underlying strategy in any unseen Google question.

---

### **Phase 1: High-Yield Foundations (Month 1)**
*Focus: Arrays, Strings, Two Pointers, Sliding Window, and Hashing.*
*   **Goal:** Build momentum using the 22 problems shared between the "Blind 75" and "Google Top 75" lists.
*   **Pattern Focus:** 
    *   **Sliding Window:** For contiguous range optimization (e.g., *Longest Substring Without Repeating Characters*).
    *   **Two Pointers:** For pair sums and partitioning (e.g., *3Sum*, *Trapping Rain Water*).
    *   **Prefix Sum:** For equilibrium points and range queries.
*   **Senior Signal:** Leverage your Java background to write production-ready code. Use clear variable naming and handle Java-specific edge cases like integer overflow or null inputs proactively.

### **Phase 2: The "Google Gap" & Advanced Structures (Month 2)**
*Focus: Predicate Search, Advanced Trees, and Topological Sort.*
*   **Predicate Search (Binary Search on Answer Space):** This is the most critical "Google-specific" pattern. Practice defining a monotonic predicate function for problems like *Minimum Shipping Capacity* or *Koko Eating Bananas*.
*   **Tree Recursion:** Master the **10 types of recursion**, specifically "bubble-up" (bottom-up) for tree diameters and "carry-forward" (top-down) for path sums.
*   **Topological Sort:** Essential for dependency-based problems common in Google's infrastructure (e.g., *Course Schedule II*, *Alien Dictionary*).

### **Phase 3: Complex Optimization & Design (Month 3)**
*Focus: Dynamic Programming (DP), Heaps, and Design-to-Code.*
*   **Dynamic Programming:** Frame DP as a **Directed Acyclic Graph (DAG)**. Focus on the 5 core patterns: Linear, Knapsack, Unbounded Knapsack, LCS, and LIS.
*   **Heaps/Priority Queues:** Master "Top K" and "Merge K Sorted" patterns, which are vital for processing large-scale data.
*   **Design Problems:** For L4, you must be able to implement an entire class from scratch under time pressure. Practice the **LRU Cache** (HashMap + Doubly Linked List) and **Randomized Set** (HashMap + Array) until they are automatic.

### **Phase 4: Simulation & Googliness (Month 4)**
*Focus: Mock Interviews, STAR-L Stories, and Manual Verification.*
*   **The Shared Doc Challenge:** Practice coding in a **plain Google Doc with no IDE**, no autocomplete, and no ability to run your code.
*   **Manual Verification:** Before declaring a problem finished, **dry-run your code** with a small example input to catch logic bugs—a high-value signal for L4 candidates.
*   **Googliness (Behavioral):** Prepare STAR-L stories for the 4 pillars:
    1.  **Thriving in Ambiguity:** Handling vague requirements.
    2.  **Intellectual Humility:** Receiving harsh feedback well.
    3.  **Challenging the Status Quo:** Proactively fixing broken systems.
    4.  **User-First Thinking:** Prioritizing long-term trust over short-term gains.

---

### **Execution Schedule**
| Timeframe | Weekly Commitment | Focus Area |
| :--- | :--- | :--- |
| **Weekdays** | **1.5–2 Hours** | Solve 1–2 Medium problems from the target weekly pattern. |
| **Weekends** | **6 Hours** | **Saturday:** 1 Hard problem + System Design reading. <br> **Sunday:** Mock Interview + review "silly mistakes". |

### **L4 Success Indicators**
1.  **Proactive Complexity:** You volunteer Big O time and space analysis *before* being asked.
2.  **Ambiguity Handling:** You spend the first 5 minutes asking clarifying questions and defining edge cases rather than jumping into code.
3.  **Pattern Intuition:** You can identify the optimal pattern for a Medium problem within 5 minutes.
