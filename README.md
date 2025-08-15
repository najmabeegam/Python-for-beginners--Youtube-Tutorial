# Gene Enrichment (Python, VS Code)

Beginner-friendly project following a YouTube tutorial: load a gene list → run Enrichr via `gseapy` → plot top pathways.

## How to run
python -m venv .venv
# Windows: .venv\Scripts\activate  |  macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook notebooks/01_enrichr_demo.ipynb

## Contents
- notebooks/01_enrichr_demo.ipynb
- src/enrich.py
- figures/ (plots)
