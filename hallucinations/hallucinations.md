# RAG Hallucination Detection

Step 1: Create the WikiQA dataset randomly sampling the following:
- WikiQA - Incorrect Answers (n=50)
- WikiQA - Correct Answers (n=50)

Step 2: Given the `prompt`, `llm_response`, and `context` create a RAG hallucination detector without using LLMs/GPT-4 as an evaluator. As a benchmark, `GPT-4` with few shot prompting performance is around `70.0%` on WikiQA

Step 3: Evaluate against WikiQA and document your learnings

Step 4: Refine against your baseline approach

Step 5: Consolidate learnings in a Google Colab notebook and above steps prior to our call
