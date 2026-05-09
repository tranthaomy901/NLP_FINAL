# Vietnamese Financial News Summarization

This repository contains the source code, dataset, and final report for a Vietnamese text summarization project. The project focuses on building an automatic summarization system for financial and economic news articles collected from VnExpress.

The main objective is to fine-tune pretrained encoder-decoder models to generate concise Vietnamese summaries while preserving important information, especially numerical values such as money, percentages, dates, quantities, and statistics.

---

## 1. Project Overview

Text summarization is an important Natural Language Processing task that aims to shorten long documents while keeping the most important information. In this project, the summarization task is applied to a specialized domain: Vietnamese financial and economic news.

Financial and economic articles often contain many numerical details. Therefore, the generated summaries must not only be fluent and concise but also accurate in terms of numerical information.

The project focuses on the following goals:

- Build a Vietnamese summarization dataset from VnExpress articles.
- Preprocess and clean the collected data.
- Split the dataset into training, validation, and testing sets.
- Fine-tune pretrained summarization models.
- Evaluate model performance using standard summarization metrics.
- Analyze numerical accuracy and summary length compliance.
- Experiment with Reinforcement Learning to improve summarization quality.

---

## 2. Project Structure

```text
.
├── data/
├── report/
├── scr/
└── README.md
