# Week 1 — Generative AI Learning Journal

## Week in One Sentence

This week I learned how to structure LLM API calls more carefully, with attention to prompts, tokens, errors, and response handling.

## What I Practiced

- Calling an LLM API from code
- Structuring system and user messages
- Using parameters such as `temperature` and `max_tokens`
- Thinking about input limits and error handling
- Improving prompt wording to make outputs more predictable

## Key Takeaways

1. **API integration is more than sending a request.**  
   A reliable implementation also needs validation, error handling, token awareness, and clear message structure.

2. **Generation settings affect output behavior.**  
   Temperature and token limits can influence consistency, length, and variability.

3. **Prompt wording matters.**  
   Clear constraints make the expected output easier for the model to follow.

## Challenge

The main challenge was completing the implementation within limited time while still handling the important edge cases.

## How I Approached It

I focused first on the essential workflow, then improved the code by adding stronger constraints and safer handling around the API call.

## Self-Evaluation

**3 / 5 — Good progress, with more room to practice.**

## Teach-Back Topic

### Temperature: Controlling Output Variability

For a short teach-back, I would explain how lower and higher temperature values affect the variability of model responses and why the right setting depends on the task.

## Next Step

Continue building small LLM applications and move from simple API calls toward more structured workflows such as search, retrieval, and agents.
