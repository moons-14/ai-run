# Serial Example
This example demonstrates how to use the AI runner to run a simple serial LLM flow.

This is an implementation of a flow that receives input from the user and generates a document based on the content of that input by generating a paragraph structure.

## Flow Files
- `1_overview.input.md`: File that defines the input from the user
- `2_paragraph.llm.md`: File that defines the LLM model and prompts that generate paragraph structure
- `3_document.llm.md`: File that defines the LLM model and prompts that generate the final document