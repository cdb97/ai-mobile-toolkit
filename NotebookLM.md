# NotebookLM Prompts

[← Back to Repository](/README.md)

## Table of Contents
- [Create Quiz based on Sources in Notebook](#create-quiz-based-on-sources-in-notebook)
- [Create a set of Flashcards](#create-a-set-of-flashcards)

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
```

## Create a set of Flashcards

```text
Create a set of high-quality flashcards for my [Exam Name/Course Title].

# Instructions:

* Front of Card: Use the specific questions found in the file [Question Source File].

* Back of Card: Provide the corresponding answer from [Answer Key File].

* Context: Refer to [Course Materials/Textbooks] only if necessary to clarify technical terms or expand on brevity.

* Format: Present the output as a table with two columns: "Question" and "Answer".
```