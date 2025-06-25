# 📢 Whisper Amharic ASR Model Evaluation

This project provides a complete pipeline for evaluating Whisper-based Automatic Speech Recognition (ASR) models on Amharic language datasets. It computes **Word Error Rate (WER)** and **Character Error Rate (CER)** across multiple model checkpoints and saves inference results to CSV for further analysis.

---

## 🎯 Objectives

- Load pre-trained Whisper ASR models from Hugging Face
- Run speech-to-text inference on Amharic audio datasets
- Compute sentence-level and overall WER/CER scores
- Export prediction results and logs in structured format

---

## 🧰 Dependencies

Install required packages:

```bash
pip install transformers datasets torchaudio jiwer pandas tqdm
