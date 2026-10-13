
## Experiment 4: Prompt Failure Diagnosis and Correction

### Aim
To identify prompt failures, understand their causes, and improve
prompts using the Gemini API.

### Problem Statement
Three problematic prompts are tested for factual errors,
format constraint violations, and possible over-refusal.

### Tools Used
- Python
- Google Colab
- Gemini API
- google-genai library

### Procedure
1. Send each original prompt to Gemini.
2. Print the original response.
3. Identify the potential failure type and suspected cause.
4. Send a corrected prompt to the same model.
5. Print and compare the improved response.

### Result
The experiment compares original and corrected prompts to examine
factual accuracy, formatting, and appropriate responses to
harmless educational requests.
