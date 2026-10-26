# Olist 360 — E-Commerce Lakehouse, Analytics & SLA MLOps

End-to-end Data Engineering, Analytics and MLOps project on the
[Olist Brazilian E-Commerce dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

**Stack:** DuckDB · dbt · Pandera · LightGBM · MLflow · Evidently · FastAPI · Streamlit

## Setup

```bash
python3.12 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
kaggle datasets download -d olistbr/brazilian-ecommerce -p data/raw --unzip
```
