# GitHub portfolio publishing plan

## One-time profile setup

1. On GitHub, create a **public** repository named exactly `blellouay` under account `blellouay`.
2. Upload the root `README.md` from this package. GitHub will display it on your profile.
3. Add a profile image, location (optional), a professional bio, and verified LinkedIn/portfolio links if available.
4. Pin up to six repositories in **Profile → Customize your pins**.

Suggested bio:
> Data Science Engineering Student | AI/ML, RAG & NLP | Python · PyTorch · Qdrant | Building reliable AI systems

## Suggested pinned repositories, in order

1. `Research-Paper-Assistant-using-RAG` — strongest applied RAG/internship case study.
2. `enterprise-ai-copilot` — engineering discipline and retrieval evaluation.
3. `RNN-LSTM-and-BiLSTM-for-Time-Series-Forecasting` — rigorous benchmarking.
4. `credit_card_fraud_detection` — financial ML and explainability.
5. `Lung_Cancer_Detection_with_CNNs` — computer vision breadth.
6. `ForecastIQ` — if documented and reproducible; replace with the financial sentiment analysis repository when published.

## Repositories worth publishing from existing CV work

**Priority A — Publish once source code and permissible data are ready**

- `financial-news-sentiment-lora-vs-tfidf`: Gemma 2 2B / LoRA vs TF-IDF + logistic-regression. Explain split, class metrics, limitations, compute costs, and reproducibility. Include model/license compliance.
- `client-default-risk-scoring`: logistic regression and XGBoost, ROC-AUC, SHAP, leakage precautions.

**Priority B — Support breadth**

- `patient-measurement-spring-boot`: Spring Boot, JPA/Hibernate, H2, CSV ingestion, query methods and tests.
- A Sagemcom internship case study only if the employer permits publication; use fabricated/sample data and remove confidential details.

## Make every pinned repository presentable

- A descriptive one-line GitHub repository description and relevant topics.
- Project README: objective, dataset/provenance, methodology, architecture, reproducible install/run steps, results (including baselines and splits), limitations, and visuals.
- `requirements.txt` or `pyproject.toml`/environment file; explicit Python version.
- A clean directory structure (`src/`, `notebooks/`, `tests/`, `assets/`), with large datasets/models excluded or linked to lawful sources.
- No credentials, personal information, confidential employer documents, proprietary datasets, or unlicensed weights.
- A license only if you own the code and wish to grant rights.
- Meaningful commit messages; remove generated files and sensitive artifacts from Git history before publishing.

## A realistic 1-week implementation sequence

Day 1: Create `blellouay` profile repository and upload README.
Day 2: Rewrite README for Research Paper Assistant and add a diagram/screenshot if available.
Day 3: Add tests, evaluation and architecture notes for Enterprise AI Copilot.
Day 4: Improve forecasting repo metrics, dataset documentation, and charts.
Day 5: Improve fraud detection repo and clearly explain leakage/imbalance/SHAP.
Day 6: Publish financial-news sentiment repository from your real code, without model checkpoints or restricted data.
Day 7: Review all links and pick the strongest six pins.

## Publishing via Git (when `blellouay` is empty)

```bash
git clone https://github.com/blellouay/blellouay.git
cd blellouay
# Copy this package's README.md into this folder
git add README.md
git commit -m "Add professional GitHub profile README"
git push origin main
```

If the GitHub repo already has a README, edit that file rather than overwriting others without reviewing.
