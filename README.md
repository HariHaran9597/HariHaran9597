# Hi, I'm Hari Haran

ML/AI engineer at Wipro, based in Bengaluru. I build tools for document question answering, local shell assistance, ML monitoring, and data analysis.

[Portfolio](https://hariharan-ai.vercel.app/) · [LinkedIn](https://linkedin.com/in/hariharan9597) · [Email](mailto:rhariharan.ai@gmail.com)

## Selected projects

Each project below states how to try it and what its evidence currently supports. Public demos are portfolio prototypes; local tools and simulated experiments are labelled separately.

| Project | What it helps with | Evidence and current status | Try it |
| --- | --- | --- | --- |
| [Policy Auditor](https://github.com/HariHaran9597/policy-auditor) | Find policy answers with page and line citations that a reader can verify. | Public Streamlit demo. RAGAS faithfulness 0.986 on 14 scored questions from a 16-question synthetic corpus; two judge calls timed out. | [Web demo](https://policy-auditorr.streamlit.app/) · [Evaluation](https://github.com/HariHaran9597/policy-auditor/blob/main/reports/ragas_report.md) |
| [nl2sh+](https://github.com/HariHaran9597/nl2sh-Junior-Shell-Assistant) | Translate an English request into a Bash command, with explanations and advisory risk checks. | Local CLI with a fine-tuned 1.5B GGUF model. Execution agreement 166/300; conservative gradeable-only agreement 44.8%. Windows environment limitations are documented. | [Install and use](https://github.com/HariHaran9597/nl2sh-Junior-Shell-Assistant#quick-start) · [Methodology](https://github.com/HariHaran9597/nl2sh-Junior-Shell-Assistant/blob/main/TRAINING_RESULTS.md) |
| [ThreadForge](https://github.com/HariHaran9597/influencer-thread-pipeline) | Draft cited social posts with a research, checking, and revision workflow. | Local FastAPI app with deterministic mock mode. The 20-topic mock benchmark checks workflow behaviour, not real-world factual accuracy or engagement. | [Run locally](https://github.com/HariHaran9597/influencer-thread-pipeline#quickstart) |
| [Churn MLOps](https://github.com/HariHaran9597/churn-mlops-pipeline) | Demonstrate prediction serving, request logging, drift detection, and retraining. | Local Docker Compose prototype on IBM Telco data with simulated traffic. Reported AUC 0.835 and recall 0.815. Retraining saves an artifact; the API must restart to load it. | [Setup](https://github.com/HariHaran9597/churn-mlops-pipeline#-quick-start) |
| [Retail Demand Forecasting](https://github.com/HariHaran9597/Retail-Demand-Forecasting) | Explore retail demand patterns and forecasting experiments. | Public dashboard on historical M5 data. Recorded holdout RMSE 98.65 versus baseline 306.13; evaluation assumptions and scenario recommendations are documented. | [Dashboard](https://retail-demand-forecastingg.streamlit.app/) · [Recorded results](https://github.com/HariHaran9597/Retail-Demand-Forecasting/blob/main/outputs/models/metrics.json) |
| [Support Ticket RAG](https://github.com/HariHaran9597/Support-Ticket-RAG) | Retrieve relevant historical tickets and draft answers with ticket citations. | Public demo. Reported Hit@3 71% and Hit@5 86% on a 28-question evaluation, including three out-of-domain questions. | [Web demo](https://support-ticket-rag.streamlit.app/) · [Evaluation](https://github.com/HariHaran9597/Support-Ticket-RAG#-running-the-evaluation-suite) |

## Technical interests

Python, PyTorch, Hugging Face Transformers, QLoRA, RAG, LangGraph, FastAPI, Docker, MLflow, Evidently, SQL, and Streamlit.

I document model and dataset sources, evaluation conditions, and limitations in the repositories. Benchmark results describe experiments; they do not establish customer adoption or business impact.

## Research and other work

- [Medical image classification paper, IEEE ICBSII 2025](https://doi.org/10.1109/ICBSII61384.2025.10813225)
- [Math Solver](https://github.com/HariHaran9597/Math-solver): QLoRA training and inference notebooks, with a [Hugging Face demo](https://huggingface.co/spaces/justhariharan/Math-Solver).
- [A/B Testing](https://github.com/HariHaran9597/A-B_Testing): a simulated experiment for practising statistical decisions; results are not measured customer outcomes.
- [Other public repositories](https://github.com/HariHaran9597?tab=repositories)
