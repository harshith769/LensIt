# LensIt

## Explainable AI Framework for Real-Time Content Trust Scoring

> **Status:** Active Research & Architecture Design

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-PyTorch-red)
![NLP](https://img.shields.io/badge/NLP-Transformers-green)
![FastAPI](https://img.shields.io/badge/API-FastAPI-009688)
![Status](https://img.shields.io/badge/Research-Active-success)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## Project Overview

**LensIt** is an ongoing AI research project that aims to estimate the trustworthiness of digital content using Explainable Artificial Intelligence (XAI), Natural Language Processing (NLP), and Machine Learning.

Unlike traditional misinformation detection systems that simply classify content as *real* or *fake*, LensIt is designed to generate an interpretable **Trust Score (0–100)** while explaining the factors that contributed to the prediction.

The long-term objective is to build a transparent AI-powered decision support system that helps users evaluate online information with confidence.

---

## Problem Statement

The volume of digital information is growing exponentially, making it increasingly difficult to distinguish trustworthy content from misinformation.

Most existing solutions provide only a binary prediction without explaining:

* Why was this prediction made?
* Which linguistic patterns influenced the decision?
* How reliable is the source?
* How confident is the model?

LensIt focuses on building explainable trust scoring rather than simple classification.

---

## Project Objectives

* Build an explainable content trust scoring framework.
* Combine linguistic, semantic and source credibility signals.
* Research interpretable Machine Learning techniques.
* Integrate Transformer-based language models.
* Develop scalable REST APIs for real-time inference.
* Provide transparent explanations using Explainable AI.

---

## Proposed System Architecture

```text
Input Text / URL
        │
        ▼
Content Extraction
        │
        ▼
Text Preprocessing
        │
        ▼
Feature Engineering
        │
        ▼
Source Credibility Analysis
        │
        ▼
Machine Learning + Transformer Models
        │
        ▼
Trust Score Prediction
        │
        ▼
Explainability Layer (SHAP)
        │
        ▼
FastAPI REST API
        │
        ▼
Dashboard / Client Applications
```

---

## Planned Features

* Explainable Trust Score (0–100)
* Source Credibility Analysis
* NLP-based Feature Engineering
* Transformer-based Semantic Analysis
* Explainable AI using SHAP
* FastAPI REST API
* Modular ML Pipeline
* Production-ready Deployment

---

## Technology Stack

| Category         | Technologies              |
| ---------------- | ------------------------- |
| Programming      | Python                    |
| Machine Learning | Scikit-learn              |
| Deep Learning    | PyTorch                   |
| NLP              | Hugging Face Transformers |
| Backend          | FastAPI                   |
| Explainability   | SHAP                      |
| Data Processing  | Pandas, NumPy             |
| Visualization    | Matplotlib                |

---

## Repository Structure

```text
LensIt
│
├── assets/
├── datasets/
├── docs/
│   ├── Future_Work.md
│   ├── Literature_Review.md
│   ├── Project_Overview.md
│   ├── Research_Roadmap.md
│   ├── System_Architecture.md
│   └── Weekly_Progress.md
│
├── models/
├── notebooks/
├── src/
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Current Progress

### Completed

* Project Vision
* Problem Definition
* Literature Survey
* High-Level System Architecture
* Repository Structure
* Research Roadmap
* Technology Stack Selection

### In Progress

* Dataset Evaluation
* Feature Engineering Research
* Baseline Model Design

### Planned

* Dataset Preparation
* TF-IDF Baseline
* Logistic Regression
* Random Forest
* XGBoost
* BERT Fine-Tuning
* SHAP Explainability
* FastAPI Backend
* Docker Deployment
* Cloud Deployment

---

## Research Roadmap

| Phase                        | Status         |
| ---------------------------- | -------------- |
| Research & Literature Survey | ✅ Completed    |
| Architecture Design          | ✅ Completed    |
| Dataset Collection           | 🔄 In Progress |
| Feature Engineering          | 🔄 In Progress |
| Baseline Machine Learning    | ⏳ Planned      |
| Transformer Models           | ⏳ Planned      |
| Explainable AI               | ⏳ Planned      |
| Backend Development          | ⏳ Planned      |
| Deployment                   | ⏳ Planned      |

---

## Repository Status

This repository currently documents the research, architecture, design decisions, and implementation roadmap of LensIt.

Code will be added incrementally as each research milestone is completed.

---

## Future Scope

* Multi-language support
* Browser Extension
* News Aggregation
* Real-time API Service
* Dashboard Analytics
* Cloud-native Deployment
* Mobile Application

---

## Author

**R. Sai Harshith**

AI & Data Science Undergraduate

Chaitanya Bharathi Institute of Technology (CBIT)

Hyderabad, India

---

## License

This project is licensed under the MIT License.

---

⭐ **If you find this project interesting, consider starring the repository.**
