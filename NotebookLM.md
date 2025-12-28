# NotebookLM Prompts

[← Back to Repository](/README.md)

## Table of Contents
- [Create Quiz based on Sources in Notebook](#create-quiz-based-on-sources-in-notebook)
- [Create a set of Flashcards](#create-a-set-of-flashcards)
- [Study tutor](#Study-tutor)

## Create Quiz based on Sources in Notebook

```text
Create a comprehensive practice exam with 50 multiple-choice questions.

# Instructions:

* Question Source: Base the questions on the specific items found in [Insert Question Source File/Course Name].
* Answer Key: Use the content in [Insert Answer Key/Reference Material] to determine the correct answer for each question.
* Distractors: For every question, generate 3 plausible but incorrect options (distractors). Derive these from [Insert Supporting Materials/Textbooks] to ensure they sound technical and relevant, but are factually wrong for the specific question asked.

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

## Study tutor

```text
Act as my interactive study tutor. I want to master the material by going through the [FILE NAME] file one learning goal at a time.

For each learning goal, please follow this exact structure:

* The Goal: State the current learning goal from the [FILE NAME] file.

* The Theory: Provide the detailed theoretical explanation for this specific goal, pulling information exclusively from the [FILE NAME] file.

* Deep Learning Application: Do not just give me an example. Instead, set up a relevant business scenario and ask me a question to start building a concrete example together. We will discuss this example until I fully grasp the concept.

Please stop after step 3 and wait for my answer. Do not move to the next learning goal until I tell you to. Start with the first learning goal now.
```
