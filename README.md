# Internal Company RAG

Internal document assistant (RAG) with role-based access control.
Demo corpus: synthetic documents of the fictional company "Penguin Cloud".

## Quickstart
```bash
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt -r requirements-dev.txt
pytest
ruff check . && ruff format --check .
```

## Layout
| Path | Purpose |
|---|---|
| `src/ingestion/` | Load documents |
| `src/chunking/` | Split text into chunks |
| `src/embeddings/` | Text to vectors |
| `src/vectordb/` | Vector DB operations |
| `src/retrieval/` | Similarity search with access filtering |
| `src/prompts/` | Prompt templates |
| `src/llm/` | LLM client |
| `src/api/` | API endpoints |
| `src/utils/` | Shared helpers |
| `tests/` | Unit and integration tests |
| `data/raw/` | Synthetic documents (versioned) |
| `eval/` | Golden set and evaluation scripts |
| `docs/` | Experiments log and ADRs |
| `config.yaml` | All tunable settings |
## Deneme

Bu bir test PR'ıdır - otomasyon denemesi.

Küçük deneme notu: pipeline tetikleme testi.

selam ben sherlock
