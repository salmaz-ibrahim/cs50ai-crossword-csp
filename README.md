# Crossword CSP Solver 🧩🤖

A Constraint Satisfaction Problem (CSP) solver built as part of “CS50’s Introduction to Artificial Intelligence with Python”.

This project solves crossword puzzles using:

* Constraint Satisfaction Problems (CSP)
* Node Consistency
* Arc Consistency
* AC3 Algorithm
* Backtracking Search
* Minimum Remaining Values (MRV)
* Least Constraining Value (LCV)
* Degree Heuristic
* Recursive Search
* Constraint Propagation

---

# 📚 Concepts Implemented

## 1. Node Consistency

Enforces unary constraints by removing words from domains that do not match the required variable length.

---

## 2. Arc Consistency

Ensures that neighboring variables remain compatible at overlapping positions.

---

## 3. AC3 Algorithm

Applies constraint propagation across the entire crossword by revising arcs and reducing impossible domain values.

---

## 4. Backtracking Search

Uses recursive search to explore possible assignments while reverting invalid states.

---

## 5. MRV Heuristic (Minimum Remaining Values)

Chooses the variable with the fewest remaining domain values first.

---

## 6. Degree Heuristic

Breaks MRV ties by selecting the variable connected to the largest number of neighboring variables.

---

## 7. Least Constraining Value (LCV)

Orders domain values based on how few neighboring values they eliminate.

---

# 🧠 Example Output

```text
██████████████
███████M████R█
█INTELLIGENCE█
█N█████N████S█
█F██LOGIC███O█
█E█████M████L█
█R███REASON█V█
███████X████E█
██████████████
```

---

# 🛠 Technologies Used

* Python
* CSP Algorithms
* Recursive Search
* Heuristic Optimization

---

# 🚀 Learning Outcome

This project helped strengthen understanding of:

* AI search algorithms
* Constraint propagation
* Recursive problem solving
* Heuristic optimization
* Intelligent search systems

---

![Status](https://img.shields.io/badge/status-completed-brightgreen)
![Language](https://img.shields.io/badge/language-python-blue)
![AI](https://img.shields.io/badge/focus-CSP%20%26%20AI-orange)
![Course]([https://img.shields.io/badge/cours](https://img.shields.io/badge/cours)
