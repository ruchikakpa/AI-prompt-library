# AI Evaluation Prompts

## 1. AI Output Evaluation Prompt

```text
Act as an AI content evaluator. Evaluate the following AI-generated response against the task requirements.

Original task: [PASTE TASK]
AI response: [PASTE RESPONSE]

Evaluate based on:
- Instruction following
- Accuracy
- Completeness
- Clarity
- Tone alignment
- Factual reliability
- Formatting
- Safety or ethical concerns

Provide:
- Score out of 10
- Strengths
- Weaknesses
- Missing elements
- Suggested improved response
```

## 2. Rubric-Based Evaluation Prompt

```text
Evaluate the AI response using this rubric:

Task: [TASK]
Response: [RESPONSE]
Rubric: [PASTE RUBRIC]

Return:
- Criterion-wise score
- Justification for each score
- Overall score
- Final recommendation: Accept / Needs Revision / Reject
```
