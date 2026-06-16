# Programming Misconceptions Question Bank (Python)

This repository contains a curated and empirically validated bank of 90 diagnostic multiple-choice questions designed for the early identification of programming misconceptions in introductory Python courses. 

Every incorrect option (distractor) is pre-mapped to a specific conceptual error code, transforming student mistakes into structured, actionable pedagogical data.

---

## Misconception Taxonomy

The question bank covers 6 primary categories and 19 specific subtypes developed through a comprehensive literature review and validated against a corpus of 1,000 public student posts from Harvard's r/CS50 forum.

| Code | Category | Core Misconception |
| :---: | :--- | :--- |
| **C1** | Math analogy | Code works like algebra (implicit multiplication, unsolved equations). |
| **C2** | Numeric/text types | Numeric strings behave like numbers. |
| **V1** | Inverse assignment | Assignment is commutative like an equation. |
| **V2** | Permanent binding | Primitive variables remain linked after assignment. |
| **V3** | Auto-initialization | An undeclared variable defaults to zero or null. |
| **V4** | Boolean opacity | Comparisons can only be used inside `if`/`while`. |
| **S1** | Sequentiality failure | Code does not execute top-down; lines interact simultaneously. |
| **S2** | Simultaneous exec. | Both branches of `if`/`else` can execute. |
| **S3** | if/while confusion | `if` repeats its block while the condition holds. |
| **S4** | Magic/abrupt loop | The loop knows when to stop on its own. |
| **F1** | print vs return | Printing a value makes it available to the rest of the program. |
| **F2** | Local/global scope | Modifying a local variable alters the global one. |
| **F3** | Pass by name | The argument must match the parameter name. |
| **R1** | 1-based indexing | The first list element is accessed with index 1. |
| **R2** | Mutation by ref. | Assigning a list to another variable creates an independent copy. |
| **D1** | Access by iteration | To get a dict value, iterate with `for` instead of using the key. |
| **D2** | Keys as indices | Dicts are accessed with `d[0]`, `d[1]`, like lists. |
| **D3** | Silent missing key | Accessing a missing key returns `None` or `0`. |
| **D4** | Keys vs values iter. | `for x in d:` yields values, not keys. |

---


This question bank serves as the analytical foundation for an AI-supported formative assessment platform piloted in the Introduction to Programming course at Universidad Técnica Federico Santa María (UTFSM).
