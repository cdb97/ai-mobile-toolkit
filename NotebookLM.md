# NotebookLM Prompts

[← Back to Repository](/README.md)

## Table of Contents
- [Create Quiz based on Sources in Notebook](#create-quiz-based-on-sources-in-notebook)

## Create Quiz based on Sources in Notebook

```text
Create a comprehensive practice exam with 50 multiple-choice questions.

# Instructions:

* Question Source: Base the questions on the specific items found in [Insert Question Source File/Course Name].
* Answer Key: Use the content in [Insert Answer Key/Reference Material] to determine the correct answer for each question.
* Distractors: For every question, generate 3 plausible but incorrect options (distractors). Derive these from [Insert Supporting Materials/Textbooks] to ensure they sound technical and relevant, but are factually wrong for the specific question asked.
* Format: Present the output as a numbered list from 1 to 50.

# Format per question:

[Question Number]. [Question Text]

A) [Option]
B) [Option]
C) [Option]
D) [Option]

Correct Answer: [Letter] – [Short Explanation]