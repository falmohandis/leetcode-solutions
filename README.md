# LeetCode Solutions and Algorithm Analysis

This repository is a structured collection of my LeetCode solutions, explanations, and analytical comparisons.

The purpose of this project is to document my growth in problem solving, algorithmic thinking, data structures, and code optimization. Each problem is treated not only as a coding exercise, but also as an opportunity to compare approaches, study patterns, and improve clarity of implementation.

I am working through LeetCode problems in numerical order starting from Problem 1, while also completing selected daily challenges.

---

## Project Goals

The goals of this repository are to:

- Build a consistent archive of algorithm and data structure solutions
- Document multiple approaches to the same problem
- Compare original solutions with optimized alternatives
- Analyze time and space complexity
- Identify recurring problem-solving patterns
- Improve code readability, correctness, and efficiency
- Create a long-term technical reference for algorithmic problem solving

---

## Repository Structure

```text
leetcode-solutions/
│
├── README.md
├── progress.md
├── notes/
│   ├── patterns.md
│   ├── complexity-cheatsheet.md
│   └── mistakes-log.md
│
├── problems/
│   ├── 0001-two-sum/
│   │   ├── prompt.md
│   │   ├── my_solution.py
│   │   ├── optimized_solution.py
│   │   ├── analysis.md
│   │   └── test_cases.py
│
├── daily-challenges/
│   └── YYYY-MM-DD-problem-name/
│       ├── prompt.md
│       ├── my_solution.py
│       ├── optimized_solution.py
│       ├── analysis.md
│       └── test_cases.py
│
├── templates/
│   ├── problem_template.md
│   ├── analysis_template.md
│   └── python_solution_template.py
│
└── scripts/
    └── create_problem_folder.sh
```

---

## Folder Overview

### `problems/`

This folder contains standard LeetCode problems solved in numerical order.

Each problem has its own folder using the format:

```text
0001-two-sum
0002-add-two-numbers
0003-longest-substring-without-repeating-characters
```

Each folder includes:

| File | Description |
|---|---|
| `prompt.md` | Summary of the problem, examples, and constraints |
| `my_solution.py` | My original solution or first working approach |
| `optimized_solution.py` | A refined, improved, or alternative solution |
| `analysis.md` | Explanation, complexity analysis, and comparison |
| `test_cases.py` | Local test cases for validating the solution |

---

### `daily-challenges/`

This folder contains selected LeetCode daily challenges.

Daily challenge folders use the format:

```text
YYYY-MM-DD-problem-name
```

Example:

```text
2026-05-18-two-sum
```

---

### `notes/`

This folder contains broader notes on recurring algorithmic patterns and concepts.

| File | Description |
|---|---|
| `patterns.md` | Notes on common problem-solving patterns |
| `complexity-cheatsheet.md` | Big-O time and space complexity reference |
| `mistakes-log.md` | Recurring mistakes, corrections, and lessons learned |

---

### `templates/`

This folder contains reusable templates for documenting new problems consistently.

---

## Documentation Format

For each problem, I aim to document:

1. What the problem is asking
2. My initial approach
3. The reasoning behind the solution
4. An optimized or alternative approach
5. Time complexity
6. Space complexity
7. Important edge cases
8. The broader algorithmic pattern
9. Lessons learned from the problem

---

## Common Patterns Tracked

This repository will gradually include problems involving:

- Hash maps
- Two pointers
- Sliding window
- Binary search
- Stack
- Queue
- Linked lists
- Trees
- Graph traversal
- Breadth-first search
- Depth-first search
- Dynamic programming
- Greedy algorithms
- Backtracking
- Heaps and priority queues
- Intervals
- Prefix sums
- Union find
- Tries
- Bit manipulation

---

## Progress Tracking

Progress is tracked in `progress.md`.

Example:

| Problem # | Title | Difficulty | Status | Pattern | Date Completed |
|---|---|---|---|---|---|
| 1 | Two Sum | Easy | Completed | Hash Map | 2026-05-18 |
| 2 | Add Two Numbers | Medium | In Progress | Linked List |  |

---

## Solution Philosophy

This repository is meant to show the process of learning and refinement.

For many problems, I keep both the original solution and an improved version. The original solution captures the first working idea, while the optimized solution focuses on cleaner logic, better performance, or a more standard algorithmic pattern.

The analysis files are especially important because they explain not only what the solution is, but why it works.

---

## Primary Language

Most solutions are written in:

```text
Python
```

Other languages may be added over time.

---

## How to Add a New Problem

A helper script is included to create a new problem folder.

Example:

```bash
bash scripts/create_problem_folder.sh 0002 add-two-numbers
```

This creates:

```text
problems/0002-add-two-numbers/
```

with the following files:

```text
prompt.md
my_solution.py
optimized_solution.py
analysis.md
test_cases.py
```

---

## Long-Term Purpose

Over time, this repository should become:

- A personal algorithm notebook
- A structured archive of solved problems
- A reference for common data structure and algorithm patterns
- A record of improving solution quality over time
- A public technical portfolio showing consistency, clarity, and analytical thinking
