---
layout: single
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research.html
---

My research focuses on the intersection of **AI Engineering** and **Industrial Intelligence**, aiming to bridge the gap between AI algorithmic advances and their systematic deployment in complex industrial scenarios. Below is a detailed overview of my three interconnected research directions.

## 1. AI Engineering — From Models to Systems

The rapid evolution of AI models has created an urgent need for engineering methodologies that can manage the full lifecycle of AI-powered software — from requirements specification through development, testing, and maintenance. Unlike traditional software, AI systems exhibit data-dependent behavior, non-deterministic outputs, and evolving performance, which demand fundamentally new engineering approaches.

**Key contributions:**

- **Requirements Engineering for ML**: I developed a structured framework for analyzing and specifying requirements of machine learning applications, with particular emphasis on interpretability and explainability requirements. This work, published in AIRE (2022) and JCRD (2024, CCF-A), provides practitioners with systematic guidance for capturing the unique quality attributes of ML systems.

- **Efficient Hyperparameter Optimization**: Deep learning model development requires extensive hyperparameter tuning, which is often ad-hoc and time-consuming. *BTTackler* (KDD 2024, CCF-A) introduces a diagnosis-based framework that identifies the root causes of training failures and guides optimization efficiently, reducing the search space by orders of magnitude.

- **Agile Development for Industrial AI**: As the project lead of the National Key R&D Program on "Agile Development Theory and Methods for Industrial Intelligent Software," I am developing methodologies that enable rapid iteration and reliable deployment of AI software in manufacturing environments.

## 2. Industrial Time Series Intelligence — From Data to Decisions

Industrial operations generate massive volumes of time series data from sensors, controllers, and operational logs. Making intelligent decisions from this data requires models that can handle multimodal signals, exogenous variables, domain shifts, and long-range temporal dependencies.

**Key contributions:**

- **Time Series Foundation Models**: *TimesBERT* (ACM MM 2025, CCF-A) establishes a BERT-style pre-training paradigm for general time series understanding. *TiMi* (ICML 2026, CCF-A) extends this with a multimodal mixture-of-experts architecture that integrates heterogeneous industrial signals (numeric, text, image) for unified time series modeling.

- **Exogenous Variable Integration**: Real-world time series are heavily influenced by external factors (weather, market conditions, operational schedules). *Aura* (KDD 2026, CCF-A) provides a universal framework for integrating multi-dimensional exogenous information into time series models, significantly improving forecasting accuracy in aviation and energy domains.

- **Domain-Adaptive Transfer**: Industrial time series models must adapt to new environments with limited data. *Adapt Data to Model* (ICLR 2026, CCF-A) proposes adaptive transformation optimization that enables domain-shared foundation models to generalize across diverse industrial settings without full retraining.

- **RAG for Time Series**: *Retrieval-Augmented Generation with Covariate Time Series* (KDD 2026, CCF-A) introduces a novel paradigm that retrieves relevant historical patterns and augments generation models with covariate context, opening new avenues for time series reasoning.

## 3. Trustworthy Industrial AI — From Lab to Field

Deploying AI in safety-critical industrial environments demands robustness against distribution shifts, reliability under uncertainty, and interpretability for human oversight. This direction focuses on ensuring that AI systems perform as expected when they encounter real-world conditions that differ from training data.

**Key contributions:**

- **Out-of-Distribution Detection**: *Unified OOD Detection* (EAAI 2023, JCR Q1) provides a comprehensive framework for detecting anomalous inputs in prognostics and health management systems for renewable energy, enabling early warning and graceful degradation.

- **Semi-supervised Fault Diagnosis**: Industrial fault data is scarce and expensive to collect. *Semi-supervised Adversarial Discriminative Learning* (Information Sciences 2023, JCR Q1) leverages adversarial training to achieve high-accuracy fault diagnosis for wind turbines with minimal labeled data.

- **Multi-Source Domain Adaptation**: *Multi-Adversarial Domain Adaptation* (AAAI 2018, CCF-A) enables knowledge transfer from multiple source domains simultaneously, addressing the common industrial scenario where data from several similar but distinct environments must be combined to improve target-domain performance.

---

## Research Roadmap

Looking ahead, I am pursuing the convergence of these three directions:

1. **Industrial Large Models**: Developing generative decision-making models for manufacturing that integrate time series foundation models with engineering process knowledge (MIIT High-Quality Special Project, 2024–present).

2. **Low-Code AI Development**: Building intelligent development environments that automate the engineering lifecycle of industrial AI applications, from data preparation to model deployment (Qiyuan Lab Innovation Project, 2022–2024).

3. **Trustworthy AI-by-Design**: Embedding robustness, fairness, and interpretability guarantees into the AI engineering process itself, rather than treating them as post-hoc verification steps.

The ultimate goal is a unified framework where **engineering rigor** ensures **industrial reliability**, and **domain intelligence** guides **engineering efficiency** — creating a virtuous cycle that accelerates the responsible adoption of AI in industry.
