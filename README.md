### Hi, I'm Sourabh

I'm a product data scientist with 8 years in data, working at the intersection of experimentation, personalization, and applied machine learning. I turn behavioral data into decisions PMs and product teams can act on, and I care most about the ones that hold up when the model is retrained or the traffic mix shifts.

On the side I build with LLMs, and I like testing whether the things people say about them actually hold up. Twice now they've done better than I expected.

#### Projects

[llm-data-guardrails](https://github.com/SourabhK7/llm-data-guardrails). I built 15 stats traps for LLMs (Simpson's paradox, mix shifts, peeking at A/B tests, regression to the mean, and so on), each with a matched control where the claim is actually true. I expected the models to fall for a lot of them. Claude Sonnet and Opus caught all 90 trap cases when asked to review a claim, and still named the real problem when I only asked them to write the wrong conclusion up for leadership. They also found bugs in my benchmark that my own rule-based checker missed.

[activation-insight-agent](https://github.com/SourabhK7/activation-insight-agent). A Python agent that takes funnel, retention, A/B test or anomaly data and writes up what's going on. pandas does all the math and the LLM only writes. I assumed the LLM would get the arithmetic wrong if I let it do the math, so I tested that with an LLM-as-judge eval. It didn't. The split is still worth it, but for debuggability, not accuracy.

[llm-ds-workflow](https://github.com/SourabhK7/llm-ds-workflow). The prompts I actually use for DS work: SQL drafting, A/B readouts, writing up null results, anomaly breakdowns, eval rubrics, prepping for exec questions. Each one notes where it tends to go wrong.

Older stuff: [causal inference](https://github.com/SourabhK7/Causal-Inference), [customer segmentation](https://github.com/SourabhK7/clustering-olist), [transaction prediction](https://github.com/SourabhK7/Santander-Customer-Transaction-Prediction).

#### What I work with

**Analytics and data:** SQL, Python, Databricks, Amplitude, Avo

**Methods:** A/B testing (including sequential testing), causal inference, propensity score matching, forecasting, churn and retention modeling

**ML:** logistic regression, XGBoost, LightGBM, random forests, clustering, recommender systems

**LLMs:** Anthropic API, structured outputs, tool use, LLM-as-judge evals

[LinkedIn](https://www.linkedin.com/in/sourabhkoul/)
