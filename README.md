# Bruno Franklin Gomes Muniz

I build systems that turn messy real-world documents and data into something a business can actually act on — mostly in Python, usually with a machine-learning or LLM component, and always with a human in the loop where it matters.

Currently at **thesum**. Based in Brazil. Interested in applied ML, document understanding, and the unglamorous data engineering that makes either of them work.

---

## 🔧 What I've built

**[conciliador-contabil](https://github.com/Brub539/conciliador-contabil)** — A production desktop app for a Brazilian accounting firm that turns a folder of expense documents into a ready-to-import ledger file. Deterministic parsers first (invoice XML, bank slips, PIX — all checksum-validated), then local vision OCR, then an LLM only where genuine ambiguity remains. **98.7% auto-classified** on a labelled evaluation set, with an export gate that refuses to post anything uncertain.

**[bank-marketing](https://github.com/Brub539/bank-marketing)** — Term-deposit prediction on the UCI bank marketing dataset, built around a **leakage-free chronological split** rather than the random split that inflates most published results on it. Nine model configurations across seven algorithm families, with the leaky-feature trap measured explicitly instead of quietly exploited.

**[isometric-agent-sim](https://github.com/Brub539/isometric-agent-sim)** — A procedurally generated isometric world in pure Python and pygame. Terrain from stacked cones through smoothstep terracing, a steepest-descent water-flow model with diffusion and erosion, and foraging agents on a Beta-distribution energy curve. No game engine: every sprite, down to the variable-height cube faces, is drawn from polygon math at runtime rather than loaded from an image.

---

## 🛠️ Tech I actually work in

**Languages** — `Python` · `TypeScript` · `JavaScript` · `SQL`

**ML & data** — `scikit-learn` · `LightGBM` · `CatBoost` · `PyTorch` · `TensorFlow` · `Optuna` · `pandas` · `NumPy` · `SciPy`

**LLM & retrieval** — `OpenRouter` · `Ollama` · `Genkit` · embeddings + BM25 hybrid search

**Web & infra** — `Next.js` · `React` · `Firebase` · `AWS Lambda` · `DynamoDB` · `Terraform` · `Docker` · `PostgreSQL`

---

## 🌐 Elsewhere

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/bruno-muniz-642227217)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:brunofranklin101@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/bruno.franklin1)
