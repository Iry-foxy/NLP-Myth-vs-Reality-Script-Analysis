# NLP-Myth-vs-Reality-Script-Analysis
An NLP project that analyzes fictional scripts using text preprocessing, named entity recognition, dependency parsing, TF-IDF, and transformer-based classification to distinguish mythological and realistic narrative elements

# 📜 Myth vs. Realism Analysis in Fictional Scripts Using NLP

## Overview

This project explores how Natural Language Processing (NLP) can be used to analyze fictional scripts by combining multiple NLP techniques into a single analytical workflow. Using a screenplay as input, the project performs text preprocessing, keyword extraction, named entity recognition, dependency parsing, transformer-based classification, and network visualization to distinguish mythological and realistic narrative elements.

The objective is not only to classify text but also to better understand the linguistic structure, characters, locations, and relationships that shape fictional storytelling.

---

## Objectives

- Clean and preprocess screenplay text.
- Perform word frequency and TF-IDF analysis.
- Extract named entities using spaCy.
- Identify important characters and locations.
- Analyze subject–verb–object relationships through dependency parsing.
- Classify sentences as mythological or realistic using a transformer model.
- Visualize relationships using dependency and co-occurrence graphs.

## Technologies

- Python
- NLTK
- spaCy
- Hugging Face Transformers
- scikit-learn
- NetworkX
- Matplotlib
- Regular Expressions (re)


## Workflow

```text
Load Script
      ↓
Preprocess Text
      ↓
Word Frequency Analysis
      ↓
TF-IDF Analysis
      ↓
Named Entity Recognition
      ↓
Character & Location Analysis
      ↓
Dependency Parsing
      ↓
Myth vs. Realism Classification
      ↓
Visualization
```

## Features

- Text preprocessing and tokenization
- Stop-word removal
- Word frequency analysis
- TF-IDF keyword extraction
- Named Entity Recognition (NER)
- Character frequency analysis
- Location detection and heuristic refinement
- Dependency parsing
- Myth vs. realism sentence classification
- Classification confidence visualization
- N-gram analysis
- Dependency graphs
- Co-occurrence network graphs

---

## Input

The project accepts a screenplay or script in plain text (`.txt`) format.

Example:

```
blackpanther.txt
```

## Output

The notebook generates:

- Most frequent non-stopwords
- Top TF-IDF keywords
- Named entities
- Character frequency analysis
- Location analysis
- Subject–verb–object relationships
- Mythological vs. realistic sentence classifications
- Classification confidence chart
- Dependency graph
- Co-occurrence network graph

## Future Improvements

- Support multiple screenplay and novel formats.
- Compare mythological themes across multiple works.
- Expand classification beyond binary mythological/realistic labels.
- Add sentiment and emotion analysis.
- Develop an interactive dashboard for comparative analysis.

## License

This project is intended for educational, research, and portfolio purposes.
