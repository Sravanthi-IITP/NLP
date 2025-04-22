# Dialogue Summarization and Chatbot using DailyDialog Dataset

This project aims to build a comprehensive system that:
1. Summarizes multi-turn dialogues using a pre-trained summarization model.
2. Evaluates the quality of the summaries using ROUGE metrics to estimate information loss.
3. Builds a chatbot that uses summarized history and generates appropriate responses using DialoGPT.

## 📁 Project Structure

- `Summarization and Evaluation.ipynb`: 
  - Loads and processes the DailyDialog dataset.
  - Generates ground truth and predicted summaries.
  - Computes ROUGE scores to evaluate summarization quality.

- `Chatbot.ipynb`: 
  - Implements a terminal-based chatbot.
  - Summarizes conversation history dynamically.
  - Uses DialoGPT to generate contextual responses.

## 🧠 Models Used
- **Summarization**: T5 or any other Transformer-based summarizer.
- **Chatbot**: DialoGPT (medium or large).

## 📊 Evaluation Metric
- **ROUGE** (Recall-Oriented Understudy for Gisting Evaluation): Measures overlap between predicted and reference summaries to quantify information loss.

## 📦 Requirements

```bash
transformers
datasets
nltk
torch
rouge-score
