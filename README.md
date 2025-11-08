# Mini GPT-2 from Scratch (COFFIN)

This repo contains a **GPT-2–style Transformer language model implemented from scratch in PyTorch** and trained on a small, fantasy-themed text corpus.  
It walks through text preprocessing, tokenization with GPT-2’s TikToken vocab, manual Transformer blocks, training, and text generation.  
This is an **educational, small-scale project**, not a production-ready language model.
This project was made as a part of my course project, might not be the best version but my first ever from scratch Language Model to help me understand and learn about the transformer architecture and text-generation and undertanding capabilites of LMs

---

## 🧱 Project Structure

- `notebooks/gpt2_from_scratch.ipynb`  
  End-to-end implementation:
  - data loading + cleaning  
  - TikToken-based tokenizer wrapper  
  - mini GPT-2–style model (multi-head self-attention, MLP blocks, residual + layer norm, weight tying)  
  - training loop with early stopping  
  - perplexity calculation + text generation

- `report/gpt2_report.pdf`  
  Course-style writeup describing the approach, experiments, and qualitative results.  
  ⚠️ Note: some hyperparameter details (e.g., batch size, sequence overlap, etc.) in the report do **not** perfectly match the current notebook and are kept as the original course submission.

---

## ⚙️ Setup

```bash
pip install -r requirements.txt
