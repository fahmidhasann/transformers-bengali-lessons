# Graph Report - Transformers 2  (2026-06-11)

## Corpus Check
- 13 files · ~73,472 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 45 nodes · 81 edges · 8 communities (6 shown, 2 thin omitted)
- Extraction: 81% EXTRACTED · 19% INFERRED · 0% AMBIGUOUS · INFERRED: 15 edges (avg confidence: 0.88)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `84110ba2`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- [[_COMMUNITY_Project Architecture & UI|Project Architecture & UI]]
- [[_COMMUNITY_Self-Attention Mechanism|Self-Attention Mechanism]]
- [[_COMMUNITY_Transformer Block Components|Transformer Block Components]]
- [[_COMMUNITY_Learning Foundation & Resources|Learning Foundation & Resources]]
- [[_COMMUNITY_LLM Input Processing Pipeline|LLM Input Processing Pipeline]]
- [[_COMMUNITY_Architecture Variants & Generation|Architecture Variants & Generation]]
- [[_COMMUNITY_Claude Settings & Plugins|Claude Settings & Plugins]]
- [[_COMMUNITY_Local Dev Config|Local Dev Config]]

## God Nodes (most connected - your core abstractions)
1. `Transformer Architecture Glossary` - 18 edges
2. `Transformer Architecture` - 12 edges
3. `AGENTS.md - Codebase Guide for AI Agents` - 10 edges
4. `Self-Attention Mechanism` - 9 edges
5. `Mission: Transformer Architecture Learning` - 7 edges
6. `Decoder-Only Architecture (GPT, LLaMA)` - 7 edges
7. `Multi-Head Attention` - 6 edges
8. `Transformer Architecture Resources` - 5 edges
9. `Residual / Skip Connection` - 5 edges
10. `Layer Normalization (LayerNorm)` - 5 edges

## Surprising Connections (you probably didn't know these)
- `User Preferences and Context Notes` --semantically_similar_to--> `Mission: Transformer Architecture Learning`  [INFERRED] [semantically similar]
  NOTES.md → MISSION.md
- `Learning Record: Prior Knowledge` --semantically_similar_to--> `User Preferences and Context Notes`  [INFERRED] [semantically similar]
  learning-records/0001-prior-knowledge.md → NOTES.md
- `Interactive Attention Simulator (SVG connection lines)` --conceptually_related_to--> `Self-Attention Mechanism`  [INFERRED]
  AGENTS.md → GLOSSARY.md
- `Transformer Architecture` --conceptually_related_to--> `Decoder-Only Architecture (GPT, LLaMA)`  [INFERRED]
  AGENTS.md → GLOSSARY.md
- `Transformer Architecture` --conceptually_related_to--> `Layer Normalization (LayerNorm)`  [INFERRED]
  AGENTS.md → GLOSSARY.md

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Transformer Block Core Components (Attention + FFN + Residual + LayerNorm)** — concept_self_attention, concept_ffn, concept_residual_connection, concept_layer_norm [EXTRACTED 1.00]
- **Input Processing Pipeline (Tokenization → Embedding → Positional Encoding)** — concept_tokenization, concept_embedding, concept_positional_encoding [EXTRACTED 1.00]
- **Self-Attention Computation (Q, K, V → Attention Weights)** — concept_query_key_value, concept_attention_weights, concept_self_attention [EXTRACTED 1.00]
- **Transformer Block Internal Components (FFN + Residual + LayerNorm + Multi-Head Attention)** — concept_ffn, concept_residual_connection, concept_layer_norm, concept_multi_head_attention, concept_transformer_block [EXTRACTED 1.00]
- **LLM Pipeline Sequential Flow (Tokenization → Embedding → Transformer → Softmax)** — concept_tokenization, concept_token_embedding, concept_transformer_block, concept_softmax_next_token, concept_llm_pipeline [EXTRACTED 1.00]
- **Three Transformer Architecture Variants (Encoder-Only, Decoder-Only, Encoder-Decoder)** — concept_encoder_only_architecture, concept_decoder_only_architecture, concept_encoder_decoder_architecture [EXTRACTED 1.00]

## Communities (8 total, 2 thin omitted)

### Community 0 - "Project Architecture & UI"
Cohesion: 0.28
Nodes (9): AGENTS.md - Codebase Guide for AI Agents, CLAUDE.md - Project Guide, Bilingual Parity Rule (Bangla/English twins), Dark-Mode First Theme System (localStorage), Lesson Loading via iframe, Interactive Attention Simulator (SVG connection lines), localStorage State Persistence (theme, progress, quiz), Single-Page Application Dashboard Architecture (+1 more)

### Community 1 - "Self-Attention Mechanism"
Cohesion: 0.36
Nodes (9): Dimension Splitting (Multi-Head Attention), Token Embedding (Semantic Vector Space), Layer Stacking (Hierarchical Abstraction), Multi-Head Attention, Positional Encoding, Sequence-to-Sequence (Seq2Seq) Architecture, Tokenization / BPE, Transformer Architecture Glossary (+1 more)

### Community 2 - "Transformer Block Components"
Cohesion: 0.83
Nodes (4): Layer Normalization (LayerNorm), Pre-LN (Pre-Layer Normalization Design), Residual / Skip Connection, Learning Record: FFN, Residual Connections, and Layer Normalization

### Community 3 - "Learning Foundation & Resources"
Cohesion: 0.28
Nodes (9): Feed-Forward Network (FFN), Transformer Architecture, Learning Record: Prior Knowledge, Mission: Transformer Architecture Learning, User Preferences and Context Notes, Paper: Attention Is All You Need (Vaswani et al.), Video: 3Blue1Brown Neural Networks & Transformers Series, Article: The Illustrated Transformer (Jay Alammar) (+1 more)

### Community 4 - "LLM Input Processing Pipeline"
Cohesion: 0.83
Nodes (4): Attention Weights (Softmax), Query (Q), Key (K), Value (V) Vectors, Self-Attention Mechanism, Learning Record: Self-Attention Mechanism

### Community 5 - "Architecture Variants & Generation"
Cohesion: 0.40
Nodes (6): Autoregressive Generation, Causal Masking (Upper-Triangular Mask), Decoder-Only Architecture (GPT, LLaMA), Learning Record: Decoder-Only Architecture & Causal Masking, Article: The Illustrated GPT-2 (Jay Alammar), Video: Andrej Karpathy - Let's build GPT from scratch

## Knowledge Gaps
- **6 isolated node(s):** `frontend-design@claude-plugins-official`, `Project Settings (Local)`, `Learning Record: Prior Knowledge`, `Single-Page Application Dashboard Architecture`, `Lesson Loading via iframe` (+1 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **2 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Transformer Architecture Glossary` connect `Self-Attention Mechanism` to `Project Architecture & UI`, `Transformer Block Components`, `Learning Foundation & Resources`, `LLM Input Processing Pipeline`, `Architecture Variants & Generation`?**
  _High betweenness centrality (0.347) - this node is a cross-community bridge._
- **Why does `AGENTS.md - Codebase Guide for AI Agents` connect `Project Architecture & UI` to `Self-Attention Mechanism`, `Learning Foundation & Resources`?**
  _High betweenness centrality (0.275) - this node is a cross-community bridge._
- **Why does `Transformer Architecture` connect `Learning Foundation & Resources` to `Project Architecture & UI`, `Self-Attention Mechanism`, `Transformer Block Components`, `LLM Input Processing Pipeline`, `Architecture Variants & Generation`?**
  _High betweenness centrality (0.226) - this node is a cross-community bridge._
- **Are the 8 inferred relationships involving `Transformer Architecture` (e.g. with `Decoder-Only Architecture (GPT, LLaMA)` and `Feed-Forward Network (FFN)`) actually correct?**
  _`Transformer Architecture` has 8 INFERRED edges - model-reasoned connections that need verification._
- **Are the 2 inferred relationships involving `Self-Attention Mechanism` (e.g. with `Interactive Attention Simulator (SVG connection lines)` and `Transformer Architecture`) actually correct?**
  _`Self-Attention Mechanism` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `frontend-design@claude-plugins-official`, `Project Settings (Local)`, `Learning Record: Prior Knowledge` to the rest of the system?**
  _7 weakly-connected nodes found - possible documentation gaps or missing edges._