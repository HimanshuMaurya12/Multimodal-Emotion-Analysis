# Multimodal-Emotion-Analysis
A machine learning pipeline for classifying emotional states in spoken language utterances using the MELD (Multimodal EmotionLines Dataset), developed for cognitive and behavioral modeling research.
# Spoken Language Emotion Recognition

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![NLP](https://img.shields.io/badge/Domain-NLP_%26_Speech-orange)
![Data Analysis](https://img.shields.io/badge/Data-Plotly_%26_Pandas-brightgreen)
![License](https://img.shields.io/badge/Code_License-MIT-green)

A computational framework for analyzing and classifying human emotions from conversational utterances. This project serves as the technical implementation for a case study on the **Cognitive & Behavioural Modelling of Spoken Language**.

## 📌 Project Overview
Understanding the emotional context of spoken language is a critical challenge in Human-Computer Interaction (HCI) and behavioral modeling. This project utilizes the **MELD (Multimodal EmotionLines Dataset)** to recognize and classify emotions such as Anger, Disgust, Fear, Joy, Neutral, Sadness, and Surprise within conversational dialogues.

### Key Features:
* **Automated Data Pipeline:** Scripts to clone, ingest, and process the MELD conversational datasets (`train_sent_emo.csv`, `dev_sent_emo.csv`, `test_sent_emo.csv`).
* **Emotion Classification:** Modeling techniques applied to sequence data to predict utterance-level emotional states.
* **Research Artifact Generation:** Automated generation of summary statistics, pivot tables, and static delta plots (via Plotly/Kaleido) to support behavioral research papers.

## 📊 The MELD Dataset
The Multimodal EmotionLines Dataset (MELD) is an extension of the popular EmotionLines dataset, featuring multi-party conversations extracted from the TV show *Friends*. 
* The dataset is automatically cloned directly from the [official MELD repository](https://github.com/declare-lab/MELD) during the initial notebook execution.

## 📁 Repository Structure
* `/notebooks`: Contains the core implementation in `Emotion_Recognition_Code.ipynb`.
* `/paper_artifacts`: Directory for generated outputs, including `summary_table.csv`, `full_results.csv`, and visualizations like `delta_plot.png`.

## 🚀 Getting Started

**1. Clone the repository:**
```bash
git clone [https://github.com/yourusername/Spoken-Language-Emotion-Recognition.git](https://github.com/yourusername/Spoken-Language-Emotion-Recognition.git)
cd Spoken-Language-Emotion-Recognition
