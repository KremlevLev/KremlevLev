# 𝔏𝔢𝔳 𝔎𝔯𝔢𝔪𝔩𝔢𝔳
> *"Building things from scratch until they work."*

ML Engineer focused on LLM systems, AI agents and deep learning.  
MIREA — Artificial Intelligence & Machine Learning. Hackathon finalist. Building transformers on JAX for fun.

---

## ⚔️ About
I build end-to-end ML systems — from raw data and feature engineering to production inference and deployment. Currently deep into LLM internals, agent architectures and RL theory.

---


## 𝔓𝔯𝔬𝔧𝔢𝔠𝔱𝔰

### **🏦 High-Load RAG Pipeline** — Alfa-Bank & MIPT Hackathon
*Production RAG system (~7000 queries) optimized for BERTScore-Recall-L*
* FAISS (bge-m3) + BM25 + RRF · cross-encoder reranking
* vLLM continuous batching · 2×T4 GPU-aware architecture
* Latency reduced by ~25%
* [→ github](https://github.com/KremlevLev/RAG-Pipeline-for-High-Load-Banking-Data)

---

### **🛡️ PII Leak Detection** — ARENA DATA (Top 6 / 25 teams)
*ML pipeline for personal data leak detection*
* 3-tier architecture: rule-engine → classification → scoring
* TF-IDF + LogReg · CatBoost with contextual scoring
* 35% FP reduction
* [→ github](https://github.com/the-boys-organization/Automatic-detection-of-personal-data-ArenaData-)

---

### **🎯 Retail Video OCR Pipeline** — Lenta CV Hackathon
*Production CV system for price tag extraction from video stream*
* YOLOv8 + custom IoU tracker · PaddleOCR → EasyOCR cascade
* Throughput: 7 → 19 FPS · OCR inferences reduced by 22%
* [→ github](https://github.com/the-boys-organization/LENTA-CV-PRODUCTION)

---

### **📈 Retail Turnover Forecasting** — X5 Tech Gradient (Final)
*Predictive model for store RTO forecasting · 90.45 score*
* Time-series feature engineering · gradient boosting · overfitting control
* [→ github](https://github.com/KremlevLev/X5_HSE_Grad_solution)


---

### **⚙️ BPE Tokenizer from scratch**
*Byte-level BPE tokenizer · GPT-2 regex · O(n log n) complexity*
* Built for deep understanding of LLM tokenization internals
* [→ github](https://github.com/KremlevLev/bpe-tokenizer-gpt)

---

### **🔬 LLM from Scratch — JAX**
*Transformer implementation: Self-Attention · Multi-Head · MoE · MLA*
* Researching memory efficiency and inference optimization
* RAG experiments on custom architecture — ongoing

---

## 𝔖𝔱𝔞𝔠𝔨

```python
stack = {
    "ml / dl":   ["PyTorch", "JAX", "CatBoost", "XGBoost", "Scikit-learn"],
    "llm / nlp": ["vLLM", "LangChain", "LangGraph", "FAISS", "BM25"],
    "infra":     ["Docker", "FastAPI", "SQL", "Git"],
```
<p align="center">
  <img src="https://seeyoufarm.com" alt="profile check" />
</p>

}
```

## 𝔉𝔦𝔫𝔡 𝔪𝔢

[![Telegram](https://img.shields.io/badge/Telegram-@yearofstilness-2CA5E0?style=for-the-badge&logo=telegram)](https://t.me/yearofstilness)
[![Kaggle](https://img.shields.io/badge/Kaggle-levkremlev-20BEFF?style=for-the-badge&logo=kaggle)](https://www.kaggle.com/levkremlev)
[![Gmail](https://img.shields.io/badge/Gmail-kremlevlev89-D14836?style=for-the-badge&logo=gmail)](mailto:kremlevlev89@gmail.com)
