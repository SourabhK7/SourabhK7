### Hi, I'm Sourabh

I'm a product data scientist working on experimentation, growth, and LLMs applied to real analytics work. Most of my day is A/B testing, activation and retention analysis, and building tools that make that work faster and more rigorous.

A thread runs through my side projects: I test the common claims about LLMs with experiments instead of taking them on faith. So far the models keep doing better than the folklore says, and I write up what I find either way.

---

#### Projects

**[llm-data-guardrails](https://github.com/SourabhK7/llm-data-guardrails)**: an eval for LLMs that answer questions about data. 15 statistical traps (Simpson's paradox, mix shift, peeking, regression to the mean, tracking breaks, and more), each paired with a matched control so blanket skepticism scores as badly as blanket agreement. Claude Sonnet and Opus caught all 90 trap cases when asked to review a claim, and named the real issue in all 90 when only asked to write the conclusion up for leadership. They also found bugs in my benchmark that my 15-check rule-based baseline missed.

**[activation-insight-agent](https://github.com/SourabhK7/activation-insight-agent)**: a Python agent that turns funnel, retention, A/B test and anomaly data into written diagnoses. pandas computes every number and the LLM writes the narrative. An LLM-as-judge eval of that design found a frontier model handled the arithmetic perfectly either way, so the real case for the split is determinism and debuggability, not accuracy.

**[llm-ds-workflow](https://github.com/SourabhK7/llm-ds-workflow)**: 15 prompt patterns I use for product DS work, including warehouse SQL drafting, A/B readouts, null-result framing, anomaly decomposition, LLM-as-judge rubric design, and exec Q&A prep. Each one documents its failure modes, and the templates can be rendered from Python.

Earlier work: [causal inference](https://github.com/SourabhK7/Causal-Inference), [customer segmentation](https://github.com/SourabhK7/clustering-olist), [transaction prediction](https://github.com/SourabhK7/Santander-Customer-Transaction-Prediction).

---

#### What I work with

**Analytics and data:** SQL, Python, Databricks, Amplitude, Avo

**Methods:** A/B testing (including sequential testing), causal inference, propensity score matching, forecasting, churn and retention modeling

**ML:** logistic regression, XGBoost, LightGBM, random forests, clustering, recommender systems

**LLMs:** Anthropic API, structured outputs, tool use, LLM-as-judge evaluation, eval design

---

[LinkedIn](https://www.linkedin.com/in/sourabhkoul/)
