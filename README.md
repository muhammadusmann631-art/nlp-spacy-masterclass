# Natural Language Processing (NLP) Masterclass with spaCy

Welcome to the **Complete NLP Course** repository! This project is a practical, production-oriented guide to mastering Natural Language Processing using **spaCy**—the fastest and most robust library for industrial NLP tasks.

Unlike traditional academic courses, this repository focusing on building real-world text-processing pipelines, extracting insights from unstructured text, and training custom NLP models.

---

## 🧠 spaCy NLP Pipeline Workflow
Here is how spaCy processes raw text sequentially through its industrial-grade pipeline components:

![spaCy Pipeline](https://github.com/YOUR_USERNAME/nlp-spacy-masterclass/blob/main/images/spacy_pipeline.png?raw=true)

---

## 🚀 Key Features & Course Highlights
* **Text Processing Foundations:** Tokenization, Lemmatization, and Stop Words handling.
* **Linguistic Features:** Part-of-Speech (POS) Tagging and Dependency Parsing for structural analysis.
* **Named Entity Recognition (NER):** Extracting real-world objects like Names, Dates, Locations, and training custom NER models.
* **Rule-Based Matching:** Using spaCy `Matcher` and `PhraseMatcher` for advanced regular expression-like text patterns.
* **Word Vectors & Semantic Similarity:** Measuring text similarity using pre-trained Word Embeddings (GloVe/Transformers).
* **Custom Pipelines:** Writing custom components and building custom Text Classification models.

---

## 🛠️ Tech Stack Used
* **Primary Library:** spaCy (v3.x)
* **Language Models:** `en_core_web_sm`, `en_core_web_md`, `en_core_web_lg`
* **Language:** Python
* **Supporting Tools:** NumPy, Pandas, Matplotlib (for text data analysis)

---

## 📂 Repository Structure
```text
├── 01_spaCy_Basics/          # Tokenization, Lemmatization, and Language models
├── 02_POS_and_Parsing/       # Part-of-Speech tagging and syntactic structures
├── 03_Named_Entity_Recog/    # Built-in NER and training custom entities
├── 04_Advanced_Matching/     # Rule-based matching and PhraseMatcher patterns
├── 05_Text_Classification/   # Building custom text classifiers in spaCy
├── data/                     # Raw text and dataset files
├── images/                   # Contains pipeline diagrams and visualizations
│   └── spacy_pipeline.png    # spaCy pipeline architecture diagram
└── requirements.txt          # Project dependencies
