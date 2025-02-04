# Task-Tree-Generation-using-Gemini-API

## Overview
This project focuses on generating structured task trees from unstructured natural language cooking instructions to aid robotic comprehension. The project leverages Gemini (a large language model) for prompt engineering, Python for data processing, and JSON for structured output, ensuring accurate task breakdowns for robotic execution.

## Project Structure
task_tree_generator.py → Main Python script for reading input and generating task trees.
input_file.json → Input file derived from the cafeteria menu following the given format.
output/ → Folder containing task trees as separate JSON files.
report.pdf → Analysis of different prompting approaches and their performances.

## Approach & Methodology
Prompt Engineering with Gemini → Designed and tested three prompting techniques to generate task trees.
Final Report → Documented findings.

## Output Format
Each generated task tree is stored in JSON format, including:
Input Nodes: Initial state of ingredients.
Motion Nodes: Actions required for transformation.
Output Nodes: Final state of ingredients.

## Evaluation Metrics
Accuracy is calculated as:
Accuracy = (Correctly generated task trees) / (Total task trees)​
