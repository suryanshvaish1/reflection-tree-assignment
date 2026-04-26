# Daily Reflection Tree (Deterministic Agent)

## Overview
This project is a deterministic reflection tool that guides users through a structured end-of-day reflection using a decision tree.

It is built as part of the DT Fellowship Assignment.

---

## Features

- Fully deterministic (no LLM at runtime)
- JSON-driven decision tree
- Covers 3 psychological axes:
  - Locus (control)
  - Orientation (contribution)
  - Radius (awareness)
- CLI-based interaction
- Tracks answers and axis signals
- Provides final reflection summary

---

## Project Structure
/tree/
reflection-tree.json

/agent/
main.py

tree-diagram.md
write-up.md
README.md

---

## How to Run

1. Navigate to agent folder:

2. Run the program:

---

## How It Works

- Loads tree from JSON file
- Traverses nodes based on user input
- Uses decision rules for branching
- Tracks answers and axis data
- Displays final summary

---

## Example Output

- User answers stored
- Axis-wise reflection displayed
- Final structured summary

---

## Constraints Followed

- No LLM usage at runtime
- Fixed options only
- Deterministic flow
- Structured tree-based design

---

## Author
Suryansh Vaish