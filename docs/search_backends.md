# Search backends — comparison & choice

Goal: pick 1–2 engines to prototype first (hybrid: BM25 + vectors), with on-prem/EU cloud options.

## Summary table (high level)

| Backend            | Type                 | Pros                                            | Cons / caveats                                  | Fit for OLRT |
|--------------------|----------------------|--------------------------------------------------|-------------------------------------------------|--------------|
| Elastic/OpenSearch | Full-text (BM25), kNN| Mature, fast, rich ops tooling                   | Vector search varies by version; tuning needed  | 👍 Full-text base, option for hybrid |
| FAISS              | Vector library       | Very fast ANN, many indices                      | Library (not a DB); needs plumbing              | 👍 Vector core for prototypes |
| Milvus             | Vector DB            | Scales, ANN choices, ecosystem                   | Oper. overhead vs library                       | ✅ Candidate for hybrid store |
| Weaviate           | Vector DB + modules  | Simple setup, hybrid tools available             | Vendor features vary by edition                  | ✅ Candidate for hybrid store |

## Decision (draft)

- **Baseline full-text:** OpenSearch (BM25).  
- **Vector:** start with **FAISS** for fast prototyping; evaluate **Milvus** for production.  
- Hybrid ranking layer is kept in OLRT (configurable weights, rerankers).

## Next steps

- Benchmark on pilot corpus (latency, recall@k).  
- Record configs and results in `docs/eval_results_m3.md`.
