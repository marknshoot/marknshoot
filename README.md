### Hi, I'm Marcell 👋

**AI Engineer intern candidate**, also open to Data Engineer and Data Scientist roles · 5th-semester Data Science at Binus University · East Jakarta, available now

I build AI systems and the data pipelines under them, then measure both against a baseline.

**[Portfolio](https://marcell-kristianto.vercel.app)** · **[Resume (PDF)](https://marcell-kristianto.vercel.app/assets/resume.pdf)** · **[LinkedIn](https://www.linkedin.com/in/marcell-hermawan-kristianto)** · marcellkristianto.ai@gmail.com

---

#### Work you can open

| Project | Role it shows | Result |
|---|---|---|
| **[Toko Marcell](https://github.com/marknshoot/toko-marcell)** · [live](https://toko-marcell.vercel.app) | AI Engineer | Fine-tuned CLIP (LoRA) on 5,378 fashion image–text pairs: **Recall@1 26.5% → 39.2%** on 539 held-out pairs. Hybrid BM25 + dense + image search in pgvector, a cross-encoder reranker, and a LangChain sales copilot. |
| **[Telco churn](https://github.com/marknshoot/telco-churn)** | Data Scientist | Six retention strategies costed in dollars on 986 held-out customers. A cost-chosen threshold spends **18.3% less** than discounting everyone, and the notebook says where a one-line rule wins. |
| **[ShopStream](https://github.com/marknshoot/data-pipeline)** | Data Engineer | End-to-end marketplace pipeline: Postgres + Kafka → S3 lake → Spark → dbt on ClickHouse → Metabase, orchestrated by Airflow. Star schema with SCD2, **125 dbt tests**, 101 source↔warehouse row-count checks, and a `SIGKILL` test showing **0 events lost** by the at-least-once consumer. CI runs a real `dbt build`. |

#### Published research

**Model Comparison for Toxigenic Cyanobacteria Image Classification Using Transfer Learning and Post-quantization** — ICOBAR 2025, Springer Nature LNEE 1693 (in press), 2nd of 5 authors.
EfficientNetB1 reached 96.72% test accuracy; FP16 quantization halved it to 12.8 MB with no accuracy loss. [Early access ↗](https://www.researchgate.net/publication/394857242_Model_Comparison_for_Toxigenic_Cyanobacteria_Image_Classification_Using_Transfer_Learning_and_Post-quantization)

#### Now

- **PIC, Data Seeker**: Binus Data Science Club's competition team, 15 delegates in 5 squads (since Oct 2025)
- **Senior Mentor**: SASC Binus mentor scholarship, weekly CS and data science tutoring
- **Client work**: private Hermes AI agent running on a client's own laptop, plus the handbook they run it from

#### Tools I've shipped with

**ML** PyTorch · PEFT/LoRA · CLIP · TensorFlow/Keras · scikit-learn · XGBoost · LightGBM · ONNX Runtime
**LLM** LangChain · Gemini API · RAG · tool calling · agent harnesses (Hermes, Pi)
**Data** SQL · PostgreSQL · pgvector · ClickHouse · dbt · Airflow · Kafka · PySpark · S3/Parquet · pandas · Metabase · Supabase
**Serving** FastAPI · Next.js · Docker Compose · GitHub Actions · Vercel
