# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.


## Algorithm:
Choose a test scenario: Write a factorial program in Python.

Apply different prompting techniques:

* Unstructured

* Zero-Shot

* Few-Shot

* Chain-of-Thought

* Role-Based

Record model output for each.

Compare outputs in terms of accuracy, relevance, depth, and clarity.

Analyze which prompting method yields the best results.

## Test Scenario & Prompts:
**Unstructured Prompt**
* Prompt: “Factorial program.”

* Output: Vague/incomplete (no clear code).

**Zero-Shot Prompt**
* Prompt: “Write Python program to find factorial of a number.”

* Output: Correct code but no explanation.

**Few-Shot Prompt**
* Prompt:Python program for Fibonacci series:

* Output: Contextual and correct factorial code.

**Chain-of-Thought Prompt**
* Prompt: “Explain step by step and then give Python code for factorial.”

* Output: Step-by-step explanation of factorial logic + correct Python code.

**Role-Based Prompt**
* Prompt: “You are a Python tutor. Write and explain factorial program.”

* Output: Beginner-friendly explanation + well-commented code.

## Output

The responses of the model varied depending on the prompting pattern. 

Unstructured prompts gave vague or incomplete answers, while zero-shot prompts provided correct but basic responses. 
Few-shot prompts improved creativity and context, chain-of-thought prompts gave step-by-step explanations with clarity, and role-based prompts delivered detailed, user-friendly answers.

## Result
From the analysis, it is observed that structured prompting patterns such as few-shot, chain-of-thought, and role-based give more accurate, clear, and well-organized results compared to unstructured or basic zero-shot prompts. Hence, prompt engineering plays an important role in improving the quality and depth of model responses.
