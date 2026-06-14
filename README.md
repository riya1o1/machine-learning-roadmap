# Machine Learning Roadmap

> My personal ML revision guide — theory, code and projects from scratch to advanced.

![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.10%2B-green?style=flat-square)

---

## About

This is my ML revision repo — built so I actually understand the concepts, not just use them.

Every topic has theory, working code with comments, and a mini project. Anyone learning ML can follow along.

---

## Roadmap

```mermaid
flowchart TD
    A([Machine Learning Roadmap]) --> B[01 Math for ML]
    A --> C[02 Python for ML]
    B --> D[03 ML Fundamentals]
    C --> D
    D --> E[04 Supervised Learning]
    D --> F[05 Unsupervised Learning]
    E --> G[06 Model Evaluation]
    F --> G
    G --> H[07 ML From Scratch]
    H --> I[08 Deep Learning]
    I --> J[09 NLP]
    I --> K[10 Computer Vision]
    J --> L[11 ML Deployment]
    K --> L
    L --> M([12 Capstone Projects])

    style A fill:#1a1a2e,color:#fff,stroke:#4ecca3
    style M fill:#1a1a2e,color:#fff,stroke:#4ecca3
    style B fill:#16213e,color:#fff,stroke:#4ecca3
    style C fill:#16213e,color:#fff,stroke:#4ecca3
    style D fill:#16213e,color:#fff,stroke:#4ecca3
    style E fill:#16213e,color:#fff,stroke:#4ecca3
    style F fill:#16213e,color:#fff,stroke:#4ecca3
    style G fill:#16213e,color:#fff,stroke:#4ecca3
    style H fill:#16213e,color:#fff,stroke:#4ecca3
    style I fill:#16213e,color:#fff,stroke:#4ecca3
    style J fill:#16213e,color:#fff,stroke:#4ecca3
    style K fill:#16213e,color:#fff,stroke:#4ecca3
    style L fill:#16213e,color:#fff,stroke:#4ecca3
```

---

## Sections

| # | Section | Topics |
|---|---------|--------|
| 01 | [Math for ML](./01_math_for_ml/) | Linear Algebra · Probability · Calculus |
| 02 | [Python for ML](./02_python_for_ml/) | NumPy · Pandas · Matplotlib |
| 03 | [ML Fundamentals](./03_ml_fundamentals/) | Preprocessing · Feature Engineering · Train Test Split |
| 04 | [Supervised Learning](./04_supervised_learning/) | Regression · Trees · SVM · KNN · Naive Bayes |
| 05 | [Unsupervised Learning](./05_unsupervised_learning/) | KMeans · Hierarchical · PCA · DBSCAN |
| 06 | [Model Evaluation](./06_model_evaluation/) | Confusion Matrix · ROC AUC · Cross Validation |
| 07 | [ML From Scratch](./07_ml_from_scratch/) | Core algorithms without sklearn |
| 08 | [Deep Learning](./08_deep_learning/) | Neural Networks · CNN · RNN · Transfer Learning |
| 09 | [NLP](./09_nlp/) | Transformers · BERT · Word Embeddings · RAG |
| 10 | [Computer Vision](./10_computer_vision/) | OpenCV · Object Detection · Segmentation |
| 11 | [ML Deployment](./11_ml_deployment/) | FastAPI · Streamlit · Docker |
| 12 | [Capstone Projects](./12_capstone_projects/) | End-to-end ML pipelines |

---

## What each notebook contains

```
1. What is this?        — plain English explanation
2. Why it matters       — where it shows up in real ML
3. Theory and math      — concept with visuals
4. Code                 — implemented with comments
5. Visualisation        — plots to build intuition
6. Common mistakes      — what to watch out for
7. Interview questions  — to test understanding
```

---

## Getting Started

```bash
git clone https://github.com/riya1o1/machine-learning-roadmap.git
cd machine-learning-roadmap
pip install -r requirements.txt
jupyter notebook
```



## Contributing

Found an error or have a better explanation? PRs are welcome.
If this helped you, leave a star — it helps others find it.

---

<p align="center">Built in public by <a href="https://github.com/riya1o1">Riya Singh</a></p>
