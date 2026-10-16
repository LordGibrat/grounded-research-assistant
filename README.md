# Grounded — Citation-first research assistant

**A citation-first research assistant interface for exploring academic papers.** It shows an answer beside the passages that would support it.

This is a static front-end prototype with a small built-in paper library and prepared answers. It does not parse uploaded PDFs, retrieve new passages, or call a language model.

## Run it

Open [`index.html`](index.html) in a browser. No build step, account, or API key is required.

## Portfolio / MBZUAI framing

**Research question:** Can citation-grounded language models help students understand research papers while reducing hallucinations?

The prototype demonstrates the intended interaction. A full research version would add PDF parsing, chunk retrieval, a reranker, a language model, and evaluation on answer faithfulness, retrieval recall, citation correctness, and user comprehension.

## Demo path

1. Select a paper from the library.
2. Ask a question or use one of the suggested prompts.
3. Inspect the answer confidence and supporting passages.
4. Click an evidence card to represent jumping to the source passage.

## Design direction

An editorial research workbench: quiet neutral surfaces, a lime evidence accent, a serif reading voice, and an always-visible evidence rail. The interface makes grounding a visible product feature rather than an invisible backend claim.

