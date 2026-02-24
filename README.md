# Analisis-Sentimen-MBG-dengan-Fuzzy-Mamdani-dan-VADER-InSet
This project implements a Mamdani Fuzzy Inference System for sentiment analysis on Indonesian economic news articles (MBG dataset) by integrating VADER and InSet Lexicon.

📌 Overview

Sentiment analysis on Indonesian economic news remains challenging due to lexical limitations in capturing nuance, ambiguity, and domain-specific expressions.
This project implements a Mamdani Fuzzy Inference System to classify sentiment in MBG economic news articles by integrating:
- VADER
- InSet Lexicon
- Fuzzy Logic (Mamdani Inference System)
Instead of relying solely on crisp polarity scores, this system transforms sentiment scores into fuzzy variables and applies rule-based inference to produce more gradual and interpretable sentiment classification.

🎯 Objectives

- Analyze sentiment in Indonesian economic news (MBG dataset)
- Integrate VADER and InSet Lexicon scores
- Apply Mamdani fuzzy inference for sentiment classification
- Evaluate model performance using F1-score metrics
- Identify limitations of lexicon-based approaches in economic domains

🧠 Methodology

The research workflow consists of:
1. Web Scraping
Collecting Indonesian economic news articles.
2. Text Preprocessing
Case folding
Tokenization
Cleaning
Normalization
3. Sentiment Scoring
Sentiment scoring using VADER
Polarity scoring using InSet Lexicon
4. Fuzzification
Transforming sentiment scores into fuzzy membership values.
5. Rule Base Design
Designing IF–THEN rules for sentiment classification.
6. Mamdani Inference
Applying fuzzy inference to generate output fuzzy sets.
7. Defuzzification
Converting fuzzy output into final sentiment class.

📈 Evaluation Results
Metric	Score
F1-Micro	0.51
F1-Macro	0.31
