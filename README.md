# Assignment 2 – Prompt Engineering & Chunking Strategy

This repository contains experiments demonstrating **Prompt Engineering with Negative Constraints** and a **Section-based Chunking Strategy** for Retrieval-Augmented Generation (RAG) concepts.

## Repository Contents
* `assignment_2.ipynb`: Jupyter Notebook containing Python code, prompt assertions, and chunking comparisons.
* `Assignment_2_Report.pdf`: Summary report detailing findings and retrieval test results.

## 🛠 Task 1: Prompt Engineering (Negative Constraints)
Tested three levels of prompts to evaluate control over AI-generated responses:
1. **Basic Prompt**: Standard explanation without strict limits.
2. **Negative Constraints**: Limited jargon, avoided vendor names, max 50 words.
3. **Strong Constraints**: Included real-life analogy, set 60–70 word target, forbade acronyms/bullet points.

*Key Takeaway:* Negative constraints significantly improve control over length, style, and tone.

##  Task 2: Chunking Strategy Comparison
Compared fixed-size character chunking against section-based semantic chunking:
* **Fixed-size Chunking**: Risked splitting related sentences across boundary boundaries.
* **Section-based Chunking**: Used Markdown headings (`##`) to split logical sections, keeping topic context intact for queries like *"What can SQL be used for?"*.



