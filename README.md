# 📌 Fine-Tuning RoBERTa for Multi-Label Text Classification (LoRA)

This project demonstrates **parameter-efficient fine-tuning** of a transformer model for **multi-label text classification** using **LoRA (Low-Rank Adaptation)**.

The model is fine-tuned on the **LexGLUE – ECHR-A** dataset, where each document can belong to **multiple legal articles simultaneously**.

---

## 🚀 Key Highlights

- **Model**: `roberta-base`
- **Task**: Multi-label sequence classification  
- **Dataset**: LexGLUE (`ecthr_a`)
- **Fine-tuning Strategy**: **LoRA (PEFT)**
- **Frameworks**: Hugging Face Transformers, Datasets, PEFT
- **Evaluation**: Multi-label metrics using sigmoid + thresholding

---

## 🧠 What This Project Does

- Loads and preprocesses the LexGLUE ECHR dataset
- Converts label indices into **multi-hot vectors**
- Fine-tunes RoBERTa using **LoRA adapters** for efficient training
- Uses **BCEWithLogitsLoss** for multi-label learning
- Evaluates model performance using appropriate metrics

---
