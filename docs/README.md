# OLRT Documentation

This folder will contain technical and user documentation for the Open Legal Retrieval Toolkit (OLRT).

Planned sections:
- **Installation guide** – Docker setup, local installation
- **Data import** – ETL pipeline, supported formats (PDF, DOCX, scans)
- **Search configuration** – full-text + vector search, hybrid setup
- **User interface** – search bar, filters, conversational mode
- **Examples** – demo queries and sample datasets

---

ℹ️ Documentation will be expanded continuously during project milestones (see Annex in the NGI0 application).

## What you find here

- `etl_spec.md` — ETL pipeline design (formats, OCR, cleaning, legal chunking).
- `search_backends.md` — comparison of backends (Elastic/OpenSearch, FAISS, Milvus, Weaviate) and our choice.
- `wcag_report_m3.md` — accessibility (WCAG 2.1) check and fixes.
- `eval_results_m3.md` — relevance/latency methodology and results.
- `deployment_notes_cp.md` — notes from the Czech Post pilot.
- `pilot_feedback.md` — anonymised feedback summary.
- `dissemination/` — materials for demo/workshop and outreach.

> The Letter of Intent (LOI) is **not** stored in the repository. It is available on request.

## Principles

- **Open licence:** Apache 2.0 (see `LICENSE` at the repo root).
- **Reproducibility:** scripts and configs are versioned; Docker images will be provided.
- **Accessibility:** the UI is developed with WCAG 2.1 in mind.
- **Security & compliance:** we plan to use NGI support services (security audit, licence compliance, accessibility, UX).

## Docs roadmap

- **M1:** `etl_spec.md`, `search_backends.md`
- **M3:** `wcag_report_m3.md`, `eval_results_m3.md`
- **M4:** `deployment_notes_cp.md`, `pilot_feedback.md`, `dissemination/*`
