📌 BERT Token Classification (POS Tagging & Chunking)
🚀 Overview

This project fine-tunes a BERT/DistilBERT model for Token Classification tasks:

Part-of-Speech (POS) Tagging
Chunking (Phrase Detection)

Built using Hugging Face Transformers and trained on the CoNLL-2003 dataset.

🎯 Features
✅ Tokenization using BERT tokenizer
✅ Label alignment with subword handling (-100)
✅ Fine-tuning using Trainer API
✅ Evaluation using seqeval (Precision, Recall, F1)
✅ Inference on custom sentences
✅ POS vs Chunking comparison
🔄 Pipeline

Raw Data → Tokenization → Label Alignment → Model Training → Evaluation → Inference

🛠️ Tech Stack
Python
Hugging Face Transformers
Datasets
SeqEval
