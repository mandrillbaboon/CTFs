# Oracle-9-CTF

A very easy CTF, a LLM called Oracle 9 which says it holds a secret transmission.

# Solution

To solve this CTF you need to experiment with a couple of Prompt Injections. 
<img width="705" height="787" alt="obraz" src="https://github.com/user-attachments/assets/b50185d8-5843-4313-abbe-aa9ac8a7b8c0" />

# Prompt Injection
A few notes from https://genai.owasp.org/llmrisk/llm01-prompt-injection/:
A prompt injection is defined as using the prompt to alter the LLM behavior or output. The input may force the model to incorrectly pass prompt data to other parts of the model, causing them to violate guidelines, generate harmful content, enable unauthorized access, influence decisions. The injection doesnt have to be human-readble.

## Types of prompt injection
1. Direct - from the prompt itself
2. Indirect - if the LLM has access to external sources - websites or files, the content of those sources may cause the model to alter its behaviour when being interpreted.


