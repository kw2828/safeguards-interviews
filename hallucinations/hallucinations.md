# RAG Hallucination Detection

Congrats on passing the initial screening! Next step is to design and create a RAG hallucination evaluator. You may explore using an ensemble of NLP, BERT, SLMs (e.g. Phi-3) and other techniques besides using an API-based LLM (e.g. GPT) as an evaluator. 

Be sure to document your process and experimental results. Cite any papers you've explored and open-source libraries you've explored. 

**Step 1:** Create the WikiQA dataset randomly sampling the following:
- WikiQA - Incorrect Answers (n=50)
- WikiQA - Correct Answers (n=50)

**Step 2:** Given the `prompt`, `llm_response`, and `context` create a RAG hallucination detector without using proprietary-models (e.g. anthropic, openai) as an evaluator. As a benchmark, `GPT-4` as evaluator LLM with few shot prompting performance is around `70.0%` on WikiQA. You may validate this yourself too.

**Step 3:** Evaluate against WikiQA and document your learnings

**Step 4:** Refine against your baseline approach

**Step 5:** Consolidate learnings in a Google Colab notebook and above steps prior to our call

You should budget between 5-10 hours and looking forward to our discussion.
