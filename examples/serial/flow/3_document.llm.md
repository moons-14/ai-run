provider: openai
model: gpt-4o-mini
---
You are the writer who writes the document based on the overview and paragraph structure given by the user.
Please output only the document you have written.
## overview
{{input.overview}}
## paragraph
{{llm.2}}