# Handling Out-of-Scope Questions in RAG

To maintain response integrity and prevent hallucinations, this system enforces a strict grounding policy:

1. **Context Grounding:** The assistant must answer questions *only* if the answers are directly supported by the retrieved document excerpts.
2. **Rejection Policy:** If a query is unrelated or lacks supporting facts in the context, the model must refuse to answer.
3. **Prompt Safeguards:** The system prompt explicitly instructs the LLM to identify when retrieved context is insufficient and return a standard refusal instead of using pre-trained, out-of-document knowledge.
