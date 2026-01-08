# G-BERT: Emotion Classification for Bengali Text

This repository contains a BERT-based emotion classification model fine-tuned on Bengali text. The model is designed to identify emotional categories from short to medium-length textual inputs using transformer-based NLP techniques.

## 🔍 Task
Multiclass emotion classification for Bengali text.

**Emotion Labels:**
- Optimistic
- Sadness
- Anger
- Astonished

## 🧠 Model
- Architecture: BERT (BanglaBERT-based fine-tuning)
- Frameworks: PyTorch, HuggingFace Transformers
- Approach: Supervised fine-tuning on annotated Bengali corpus

## 📊 Dataset
- Custom annotated Bengali text dataset  
- Large-scale corpus prepared and labeled manually  
- Supports emotion-level semantic analysis

## 🚀 Features
- End-to-end emotion prediction pipeline
- Batch inference on CSV files
- Match/accuracy evaluation with ground-truth labels
- Exportable predictions for analysis

## ⚙️ Usage
1. Load the trained model and tokenizer
2. Provide Bengali text input (single or CSV)
3. Run inference to obtain predicted emotions
4. Compare predictions with true labels if available

## 📁 Output
- Predicted emotion labels
- Match indicators
- Overall accuracy statistics

## 📌 Applications
- Emotion analysis in Bengali literature
- NLP research and benchmarking
- Downstream tasks such as NER, sentiment-aware systems, and LLM fine-tuning

## 📜 License
For academic and research use only.
