# DATA 542 Project: AIDev Dataset (Group 7: Yihang Wang, Aaron Sukare)

This repository contains our group project work for DATA 542 using the AIDev dataset from Hugging Face (`hao-li/AIDev`).
We researched how agentic pull requests are used and reviewed on GitHub.

## Research questions
RQ1 – Who adopts coding agents on GitHub?
RQ2 – How do agentic pull requests change code?
RQ3 – What do reviewers focus on when they review agentic pull requests?

## Repository structure
- `RQ1.ipynb` – adoption vs experience  
  - joins users with agentic PRs
  - computes tenure and experience levels
  - shows counts and a bar plot by experience group

- `RQ2.ipynb` – patch size and files touched
  - aggregates commit details to PR level
  - computes additions, deletions, total changes and files touched
  - shows summary stats and a patch size histogram

- `RQ3.ipynb` – review focus
  - loads PR comments, reviews and pull requests
  - prints shapes and a few sample rows
  - full analysis will be done for the final milestone

## Execution instructions
1. Create a Python environment.
2. Install the required packages:
   ```bash
   pip install pandas numpy pyarrow matplotlib