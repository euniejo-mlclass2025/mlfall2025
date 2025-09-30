# Lab 2 – Data Collection and Pre-Processing

This project follows a 12-step Data Engineering roadmap on a realistic e-commerce dataset.  
The goal is to load raw transactions, clean and enrich them using Python functions,  
integrate external metadata (coupons and city lookups), and finish with analytical insights.  
The final deliverables are a reproducible Jupyter Notebook and serialized datasets (CSV + JSON)  
containing the 7 required fields for grading.

## Quick Start
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook