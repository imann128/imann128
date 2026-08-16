**`$ whoami`**
```yaml
Iman Naeem — Data Science student, full-stack & systems engineer
```

**`$ cat focus.txt`**
```yaml
Correctness at the boundary:
  pipelines that can't leak the future into the past
  webhooks that can't double-fire
  backtests that don't lie
```

**`$ cat links.txt`**
 
`portfolio:` [https://imann128.github.io/](https://imann128.github.io/)
 
---

### What I work with

| Category | Stack |
|---|---|
| Languages | Python, JavaScript / React.js, C# / .NET, Java |
| APIs & Data | REST APIs, JSON, OpenAPI specs, Apify |
| Automation | Web scraping pipelines, scripting, CI/CD concepts |
| Writing | Technical blog posts, developer-facing documentation |

---

### Projects

**[tsauditor](https://github.com/imann128/tsauditor)**: Time-series data-quality auditor, live on [PyPI](https://pypi.org/project/tsauditor/). Detects irregular timestamp frequency, non-stationarity, and feature leakage before a model ever gets trained on the data. Featured in [PyCoder's Weekly Issue #745](https://pycoders.com/issues/745)
[Data Science Weekly, Issue 657](https://datascienceweekly.substack.com/p/data-science-weekly-issue-657).

**[statsmodels](https://github.com/statsmodels/statsmodels/)**: Merged PR [#9811](https://github.com/statsmodels/statsmodels/pull/9811), fixed a Hannan-Rissanen estimator constraint blocking seasonal-differencing-only ARIMA models, Merged PR [#9845](https://github.com/statsmodels/statsmodels/pull/9845), added fixed_params support to innovations_mle, and merged PR [#9915](https://github.com/statsmodels/statsmodels/pull/9915) and fixed a bug which caused ARDLResults.apply/append to lose exog lag order.

**[RelayCore](https://github.com/imann128/RelayCore)**: Webhook gateway with at-least-once delivery, Redis-backed idempotent dedup, JSONPath fan-out routing, HMAC-SHA256 verification, an SSRF guard, and a dead-letter queue for failed deliveries.

**[ReAct-Agent-From-Scratch](https://github.com/imann128/react-agent-from-scratch)**: A ReAct (Reasoning + Acting) agent framework built from scratch in Python. It has no LangChain or agent SDK. It implements the Thought/Action/Observation loop, tool dispatch, and a resumable state machine as plain, testable code. Supports human-in-the-loop approval gates, retry/backoff on LLM failures, execution tracing, and pluggable providers.

**[OGDC Equity Analysis Platform](https://github.com/imann128/OGDC)**: End-to-end pipeline over 6+ years of PSX stock data, GARCH volatility modelling, Bollinger Band backtesting, and sentiment analysis across 14 sources, with strict train/test discipline to keep the backtests honest. React.js frontend with Recharts. Live: [ogdc-project.vercel.app](https://ogdc-project.vercel.app)

**[iot-anomaly-pipeline](https://github.com/imann128/iot-anomaly-pipeline)**: Anomaly detection on NASA SMAP/MSL telemetry, benchmarking Isolation Forest, rolling z-score, and an LSTM autoencoder against labelled ground truth. FastAPI + PostgreSQL, Streamlit dashboard.

**[DevMetrics](https://github.com/imann128/DevMetrics)**: A user-analytics-focused project. Self-hosted Git telemetry service built with .NET 8, Clean Architecture, and SignalR, streaming commit activity in real time.

**[Floro Chatbot](https://github.com/imann128/Floro-Chatbot)**: Bilingual NLP chatbot handling queries in English and Urdu.
