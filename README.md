# Router-Guided RAG for Natural Questions

**Adaptive retrieval** for QA over Wikipedia, inspired by Self-RAG.

## Experiments
- Natural Questions (doc-controlled)
- 50 / 500 / 3000 examples
- RoBERTa SQuAD2 + MiniLM retriever
- DistilBERT + Logistic Regression **router**

## Results
Router improves F1 while reducing retrieval rate.

| NQ | System | F1 | Rate |
|----|--------|----|------|
| 500 | Router | **0.126** | **91%** |
| 3000 | Router | **0.100** | **75%** |

## Files
- `router-guided-rag-50.ipynb` (50)
- `router-guided-rag-500.ipynb` (500)
- `router-guided-rag-3000.ipynb` (3000)
- `POSTER.pdf`
