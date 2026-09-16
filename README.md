<h1 align="center"><em><strong><code>Coding Challenges</code></strong></em></h1>

<p align="center">
  <em>A Python-first journal of Data Structures &amp; Algorithms — solved, explained and documented.</em>
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=flat-square&logo=jupyter&logoColor=white">
  <img alt="LeetCode" src="https://img.shields.io/badge/LeetCode-Practice-FFA116?style=flat-square&logo=leetcode&logoColor=white">
  <img alt="NeetCode" src="https://img.shields.io/badge/NeetCode-150-2ea44f?style=flat-square">
  <img alt="Status" src="https://img.shields.io/badge/status-actively%20solving-blue?style=flat-square">
</p>

---

## *__`Why this repo exists`__*

I'm a **backend Python developer**. Day to day I write services, APIs and data pipelines, but the fundamentals (complexity analysis, hash maps, pointers, recursion) are what make that code *fast* instead of just *working*.

This repo is my deliberate-practice log:

- Solve a problem → **write the solution in Python**
- Explain the **intuition** before the code
- Record the **time** 
- Keep every attempt, including the brute force, so the *progression* is visible

> Notebooks over `.py` files on purpose: markdown + code + output in one place makes
> each problem a self-contained, readable explanation rather than a wall of functions.

---

## *__`Repository structure`__*

```text
Coding_Challenges/
│
├── README.md                        # you are here
│
├── 001_Leet_Code/                   # LeetCode — assorted / daily problems
│   ├── README.md
│   └── Leet_Code_Concepts.ipynb
│
└── 002_Neet_Code_150/               # NeetCode 150 — the structured roadmap
    ├── README.md
    └── Neet_Code_Concepts.ipynb
```

| Folder | Track | What's inside |
| :--- | :--- | :--- |
| [001_Leet_Code](001_Leet_Code) | **LeetCode** | Free-form problems picked up along the way |
| [002_Neet_Code_150](002_Neet_Code_150) | **NeetCode 150** | The curated 150, worked through pattern by pattern |

---

## *__`How each solution is documented`__*

Every problem follows the same template so the notebooks stay skimmable:

```markdown
### N. Problem Name :
  - Link to the problem
  - Plain-English restatement of the task
  - Intuition / approach
  - Python solution
  - Time complexity  -> O(?)
  - Space complexity -> O(?)
```

---

## *__`Running the notebooks`__*

```powershell
# clone
git clone <your-repo-url>
cd Coding_Challenges

# (recommended) isolated environment
python -m venv .venv
.\.venv\Scripts\Activate.ps1

# jupyter
pip install jupyterlab
jupyter lab
```

Or just open the folder in **VS Code** and run the `.ipynb` files directly — no extra
dependencies, everything uses the Python standard library.

---

## *__`Ground rules I followed`__*

1. **Brute force first** — get *a* correct answer, then earn the optimisation.
2. **State the complexity out loud.** If I can't, I don't understand the solution yet.
3. **Pythonic, but explicit.** `collections.Counter` is fine; one-liner golf is not.
4. **Edge cases up front** — empty input, single element, duplicates, negatives, overflow.
5. **Revisit, don't just move on.** A problem re-solved a week later is a problem learned.

---

