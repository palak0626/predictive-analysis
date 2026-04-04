#  Assignment: Multi-Threaded Matrix Multiplication

##  Overview
This project demonstrates how multithreading affects the performance of matrix multiplication.

We multiply multiple matrices using different numbers of threads and observe how execution time changes.

---
##  Objective
- Multiply multiple random matrices
- Use different numbers of threads (1 to 8)
- Measure execution time
- Show that:
  - Time decreases initially (better performance)
  - Then increases (due to overhead)

---
## Technologies Used
- Python
- NumPy (for matrix operations)
- Threading (for multithreading)
- Matplotlib (for graph)

---
##  How It Works (Step-by-Step)

1. Generate random matrices  
2. Divide matrices into chunks  
3. Assign each chunk to a thread  
4. Each thread multiplies matrices  
5. Measure total execution time  
6. Repeat for different thread counts  
7. Plot graph of threads vs time  

---

##  Experiment Details

| Threads | Behavior |
|--------|---------|
| 1      | Slow (no parallelism) |
| 2–4    | Faster (parallel work) |
| 5–8    | Slower again (overhead increases) |

---

## Graph 

<img width="703" height="556" alt="image" src="https://github.com/user-attachments/assets/739179af-451f-4661-b211-8813eeb9ebd3" />

---


##  Result

- Initially, increasing threads improves speed  
- After a certain point, performance degrades  
- This happens due to:
  - Thread creation overhead
  - Context switching
  - CPU limitations  

---
