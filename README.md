# EXP-2
# Experiment 2: Baseline vs Enhanced Prompt

## Aim
To demonstrate how prompt engineering improves the clarity, structure, and relevance of language model responses.

## Problem Statement
Compare a baseline prompt with an enhanced prompt containing role assignment, context, analogy, and output-format instructions using the Google Gemini API.

## Technologies Used
- Python
- Google Gemini API
- Google GenAI SDK
- Google Colab

## Algorithm
1. Initialize the Gemini API client.
2. Define a baseline prompt.
3. Define an enhanced prompt for the same task.
4. Send both prompts independently to the model.
5. Display the prompts and generated responses.
6. Compare response lengths and discuss the differences.

## Installation

```bash
pip install -r requirements.txt
```

## Execution

```bash
python experiment2.py
```

Enter your Gemini API key when prompted.

## Expected Output
The program displays the baseline prompt and response, the enhanced prompt and response, a word-count comparison, and a brief analysis.

## Result
The experiment demonstrates how role assignment, context, and output constraints can guide a language model to produce more structured and beginner-friendly explanations.

## Security
Never upload your Gemini API key or `.env` file to a public repository.
