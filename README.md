
# IRP-II Assignment 5
## Git, GitHub & DSA Coding Problems in Python

A collection of Python programs developed as part of the IRP-II assignment. This repository demonstrates problem-solving skills, fundamental Data Structures and Algorithms, input/output handling, testing, and Git version control practices.

---

## Student Information

- **Name:** Khilesh Kishore
- **Roll Number:** YOUR_ROLL_NUMBER
- **Assignment:** IRP-II Assignment 5
- **Language:** Python 3
- **Repository:** irp2-a5

---

## Project Structure

```text
irp2-a5/
│
├── problems/
│   ├── p1_reverse_words.py
│   ├── p2_binary_search.py
│   ├── p3_digit_sum.py
│   └── p4_pair_count.py
│
├── tests/
│   ├── p1_input.txt
│   ├── p1_expected.txt
│   ├── p1_output.txt
│   ├── p2_input.txt
│   ├── p2_expected.txt
│   ├── p2_output.txt
│   ├── p3_input.txt
│   ├── p3_expected.txt
│   ├── p4_input.txt
│   └── p4_expected.txt
│
├── README.md
└── .gitignore
```

---

## Problems Included

| No. | Problem | Concept |
|---|---|---|
| 1 | Reverse Words | String Manipulation |
| 2 | Binary Search | Searching Algorithm |
| 3 | Digit Sum | Recursion |
| 4 | Pair Count | Array / Pair Processing |

---

## Requirements

- Python 3.x
- Git
- Visual Studio Code (recommended)

No external Python libraries are required.

---

## How to Run

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Navigate to the project directory:

```bash
cd irp2-a5
```

Run individual programs:

**Problem 1 – Reverse Words**
```bash
python problems/p1_reverse_words.py
```

**Problem 2 – Binary Search**
```bash
python problems/p2_binary_search.py
```

**Problem 3 – Digit Sum**
```bash
python problems/p3_digit_sum.py
```

**Problem 4 – Pair Count**
```bash
python problems/p4_pair_count.py
```

All programs read input from standard input and display results on standard output.

---

## Testing

Test cases are stored in the `tests/` directory.

Each problem includes:
- `input.txt` – Sample input.
- `expected.txt` – Expected output.
- `output.txt` – Actual program output (where applicable).

Example: Run the binary search test on Windows CMD:

```cmd
python problems/p2_binary_search.py < tests/p2_input.txt > tests/p2_output.txt
```

Compare actual and expected output:

```cmd
fc tests/p2_expected.txt tests/p2_output.txt
```

If the files match, the test passes.

---

## Git Workflow

This project follows Git version control practices:

- Development is carried out on a separate `dev` branch.
- Changes are committed in meaningful, incremental commits.
- Work is pushed to the remote GitHub repository.
- Completed development work is merged into `main`.

---

## Learning Objectives

- Understand and implement fundamental DSA concepts.
- Develop Python programming and problem-solving skills.
- Practice standard input and output handling.
- Organize programs and test cases systematically.
- Gain practical experience with Git and GitHub.
- Maintain a structured development workflow.

---

## Author

**Khilesh Kishore**

IRP-II Assignment 5  
Python | Data Structures & Algorithms | Git & GitHub
