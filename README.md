> **Status: ENTRY_ROUTER (Portfolio Hub)**
>
> Professional portfolio showcasing production-grade semantic indexing and RAG infrastructure.

## Start Here

| Resource | Description |
|----------|-------------|
| **[Universal Protocol v4.23](https://github.com/whmatrix/universal-protocol-v4.23)** | Canonical spec: deliverable contracts, audit contracts, quality gates |
| **[semantic-indexing-batch-02](https://github.com/whmatrix/semantic-indexing-batch-02)** | Production implementation: 8.3M+ vectors indexed |
| **[research-corpus-discovery](https://github.com/whmatrix/research-corpus-discovery)** | Applied methodology: semantic search across 10 research institutions, 4,600+ documents |

> Note: [semantic-indexing-batch-01](https://github.com/whmatrix/semantic-indexing-batch-01) is a superseded foundation batch.

## Structural Analysis

- [comparative-grammar-gpt-vs-claude](https://github.com/whmatrix/comparative-grammar-gpt-vs-claude) — GPT vs Claude dialogue grammar comparison
- [structural-collaboration-primitives](https://github.com/whmatrix/structural-collaboration-primitives) — Interaction primitive definitions
- [interaction-mechanics-index](https://github.com/whmatrix/interaction-mechanics-index) — Dual FAISS indices for dialogue mechanics retrieval

---

# whmatrix.github.io

**Live site**: https://whmatrix.github.io

## Production Stats

- **Total Vectors**: 9,016,688 across 9 production datasets (batch-01 + batch-02)
- **Research Corpora**: 4,600+ documents across 10 institutions (~75,000 chunks)
- **Datasets**: Wikipedia Featured Articles, StackExchange Python, ArXiv ML Abstracts, 20 Newsgroups, SimpleWiki, IMDB, StackOverflow, AG News, Disaster Tweets
- **Model**: intfloat/e5-large-v2 (1024-dim embeddings)
- **Index**: FAISS IndexFlatIP

---

## Visual Overview

```
+-------------------------------------------------------+
|            whmatrix: Semantic Search Stack             |
+-------------------------------------------------------+
|                                                       |
|  SCALE          STANDARDS     THEORY     APPLICATION  |
|    |               |            |            |        |
|    +- 661K       +- Protocol  +- Grammar  +- 10      |
|    +- 8.35M      +- v4.23    +- Primitives  orgs    |
|                               +- Mechanics           |
|                                                       |
|  [Try Demo]  [View Specs]  [See Architecture]         |
+-------------------------------------------------------+

Vectors indexed:      9,016,688 (across 9 datasets)
Documents analyzed:   4,600+ (across 10 institutions)
Query latency:        <100ms (single query)
Embedding model:      e5-large-v2 (1024-dim, FP16)
Index type:           FAISS IndexFlatIP
```

---

## Scope

This site serves as a **presentation and routing layer**, not a full technical explanation.

- Static HTML/CSS only
- No JavaScript frameworks
- No blog or research log
- No client-specific material

All production guarantees, acceptance criteria, and verification artifacts are defined in the protocol repository.
