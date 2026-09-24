# Awesome-AI-Model-Monitoring

## Top AI Model Monitoring Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on ML/LLM Observability, Data & Concept Drift, Performance Tracking, Model Quality Monitoring & Production AI Health*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Model Monitoring**. These systems track models in production—detecting data drift, performance degradation, prediction quality issues, and LLM-specific failures—so teams can alert, debug, and retrain before users are impacted.



**Examples** include Arize AI, Fiddler AI, WhyLabs, Aporia, Evidently AI, Arthur AI, Superwise, TruEra, Monte Carlo AI, and Galileo (the category leaders).



**Open-source emphasis**: Model monitoring has strong open options. **Evidently**, **Deepchecks**, **WhyLogs**, and related libraries cover drift, performance, and LLM evals with self-hosted dashboards. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Arize AI](https://arize.com/)**  

  Leading ML and LLM observability platform for tracing, evaluation, drift, and production monitoring across traditional and generative models.



- **[Fiddler AI](https://www.fiddler.ai/)**  

  Model performance and explainability platform with monitoring, drift detection, and governance features for enterprise AI.



- **[WhyLabs](https://whylabs.ai/)**  

  AI observability platform built around data logging and monitoring, with strong support for data quality and model health (pairs with open WhyLogs).



- **[Aporia, Arthur AI, Superwise, TruEra](https://www.aporia.com/)**  

  Production ML monitoring and explainability platforms covering drift, performance, and model risk workflows.



- **[Evidently AI (cloud)](https://www.evidentlyai.com/)**  

  Commercial offering built on the popular open-source Evidently framework for ML and LLM evaluation and monitoring.



- **[Galileo, Monte Carlo AI](https://www.rungalileo.io/)**  

  Platforms focused on LLM evaluation/observability and data reliability that complement model monitoring stacks.



- **[Other commercial model monitoring platforms](https://arize.com/)**  

  Additional solutions for enterprise-scale AI observability and MLOps monitoring.



## Open-Source GitHub Projects



- **[Evidently](https://github.com/evidentlyai/evidently)**  

  Leading open-source ML and LLM observability framework—100+ metrics for drift, data quality, performance, and generative evals; reports, tests, and self-hosted monitoring UI.



- **[Deepchecks](https://github.com/deepchecks/deepchecks)**  

  Open-source validation and monitoring suite for data and models (tabular, NLP, CV)—testing from research through production, with monitoring components available open-source.



- **[WhyLogs](https://github.com/whylabs/whylogs)**  

  Open-source data logging library for profiling datasets and tracking changes over time; pairs with WhyLabs for full monitoring or can be used standalone.



- **[NannyML](https://github.com/NannyML/nannyml)**  

  Open-source library focused on post-deployment performance estimation and drift detection when ground truth is delayed or missing.



- **[Alibi Detect](https://github.com/SeldonIO/alibi-detect)**  

  Open algorithms for outlier, adversarial, and drift detection usable in custom monitoring pipelines.



- **[River / river-ml online learning](https://github.com/online-ml/river)**  

  Open tools for streaming data and incremental metrics relevant to real-time monitoring setups.



- **[MLflow, Prometheus + custom metrics](https://github.com/mlflow/mlflow)**  

  Experiment tracking and general observability stacks often extended with model performance and drift metrics in production.



- **[LLM-specific open evals](https://github.com/search?q=LLM+monitoring+OR+RAG+evaluation+open+source)**  

  Open evaluation libraries (e.g. RAGAS-style, custom judges) used to monitor generative application quality over time.



### Additional Strong Open-Source Options



- **Full open monitoring**: Evidently (reports + UI) as the primary open ML/LLM monitoring stack.

- **Validation + monitoring**: Deepchecks for suite-based testing and production tracking.

- **Logging layer**: WhyLogs for lightweight, privacy-aware data profiles.

- **No-label performance**: NannyML when outcomes arrive late.

- **Composable stacks**: Feature/prediction logging → Evidently/Deepchecks jobs → Prometheus/Grafana or Evidently UI.

- Commercial platforms still lead in multi-model estates, tracing, and enterprise alerting workflows.



**Frameworks for building custom systems**:  

**Evidently** is the strongest open foundation for model and LLM monitoring.  

**Deepchecks**, **WhyLogs**, and **NannyML** fill validation, logging, and delayed-ground-truth gaps.  

Commercial platforms (Arize, Fiddler, WhyLabs, Aporia, Arthur, etc.) provide scale, tracing, and managed ops.  

Many teams run Evidently or Deepchecks in-house for core drift/performance monitoring and adopt commercial AI observability for large multi-team estates. Fully open stacks are production-viable for most ML monitoring needs.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Model monitoring detects symptoms; root-cause analysis and retraining remain human and process responsibilities. Metrics and thresholds must be tuned to avoid alert fatigue.

- Open-source tools offer transparency and data residency but require you to operate pipelines and storage. Commercial platforms shift operational burden to the vendor. Align monitoring with your model risk and compliance requirements.



---



**Made for ML engineers, MLOps teams, and organizations running models in production.**  

Let's expand open model monitoring while recognizing the scale and workflow depth that leading commercial AI observability platforms deliver.
