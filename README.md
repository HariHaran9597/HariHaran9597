# Hariharan

I build ML systems that actually work

Right now I'm deep into applied AI: fine-tuning LLMs, building multi-agent systems, and figuring out how to make vector search fast at scale. I care about the full pipeline — from messy data to a deployed app someone can actually use.

IEEE published researcher. 4+ deployed projects with live demos. I ship.

---

### Things I've built recently

**[Cross-Modal Product Search](https://github.com/HariHaran9597/product-image-search)** — Upload a photo OR type "red canvas shoes" → get the 5 most similar products from a 44K catalog. Uses CLIP embeddings + FAISS. 91.8% Recall@5, sub-50ms search. Model artifacts live on AWS S3. → [try it live](https://visual-search-enginee.streamlit.app/)

**[PaperTrail — Research Paper Intelligence Engine](https://github.com/HariHaran9597/PaperTrail)** — Paste an arXiv link → 5 LangGraph agents parse it, explain it at 3 levels (ELI5 → Expert), score its novelty against 5,000+ papers using FAISS, and generate an interactive concept map. Runs on Groq at $0 cost. → [try it live](https://papertraill.streamlit.app/)

**[Math Solver (Fine-tuned LLM)](https://github.com/HariHaran9597/Math-solver)** — Took a 1.5B param model, fine-tuned it with QLoRA on math problems. Went from 45% → 82% accuracy using chain-of-thought + majority voting across 3 reasoning paths. Runs in <2s. → [try it live](https://huggingface.co/spaces/justhariharan/Math-Solver)

**[Retail Demand Forecasting](https://github.com/HariHaran9597/Retail-Demand-Forecasting)** — 10.9 million transactions. XGBoost + Prophet + SHAP. 72% RMSE improvement. Built a 4-page Streamlit dashboard that store managers can actually use. → [live dashboard](https://retail-demand-forecastingg.streamlit.app/)

**[Telecom Churn Prediction](https://github.com/HariHaran9597/Telecom-Churn-Prediction)** — 5 models benchmarked with MLflow. XGBoost + SMOTE gets 80%+ recall on churners. Translates predictions into ₹ revenue-at-risk so business teams actually care. FastAPI backend + Streamlit frontend. → [try it live](https://telecom-churn-predictionn.streamlit.app/)

---

### What I reach for

```
python · pytorch · scikit-learn · xgboost · faiss · clip
langchain · langgraph · hugging face · qlora · rag
fastapi · streamlit · gradio · docker · aws s3 · mlflow
postgresql · pinecone · chromadb
```

---

### Get in touch

Building something interesting? I'm open to AI/ML Engineer and Data Scientist roles.

**→** [rhariharan.ai@gmail.com](mailto:rhariharan.ai@gmail.com) · [LinkedIn](https://www.linkedin.com/in/hariharan9597)
