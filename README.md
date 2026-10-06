# Toxic-Engagement-Analysis

The Myth of Toxic Engagement: A Data-Driven Analysis of Online Discourse Overview

This project investigates whether toxic online content drives higher engagement. Using the Jigsaw Toxic Comment Classification dataset, we apply text analytics, sentiment analysis, statistical modelling, and linguistic pattern analysis to explore the relationships between toxicity, sentiment, and user interaction.

Objectives Analyse the relationship between toxicity and engagement. Examine how sentiment changes across toxicity levels. Identify linguistic patterns associated with toxic and non-toxic comments. Evaluate implications for content moderation and platform design. Dataset

Source: Jigsaw Toxic Comment Classification Dataset (Kaggle)

The dataset contains approximately 150,000 user comments labelled across six toxicity categories:

Toxic Severe Toxic Obscene Threat Insult Identity Hate Methodology Data Preprocessing Lowercasing text Removing URLs, punctuation, numbers, and special characters Handling missing values Text standardisation Feature Engineering Toxicity Score (combined toxicity labels) Sentiment Score (VADER sentiment analysis) Engagement Proxy (comment length) Analysis Toxicity vs Engagement Distribution analysis Regression modelling Sentiment vs Toxicity Sentiment score analysis Detection of sentiment blind spots Linguistic Pattern Analysis Label prevalence Label co-occurrence Word frequency analysis Key Findings Toxic content does not significantly increase engagement. Toxicity explains less than 1% of engagement variance (R² ≈ 0.007). Sentiment becomes increasingly negative with higher toxicity levels. Sentiment alone cannot reliably detect toxicity due to sarcasm, irony, and contextual language. Toxic discourse exhibits distinct linguistic and structural patterns. Technologies Used Python Pandas NumPy Matplotlib Seaborn NLTK (VADER) Scikit-learn Statsmodels Business Implications

The findings suggest that engagement-driven systems should not assume toxic content is necessary for user interaction. Combining toxicity detection, sentiment analysis, and contextual language modelling can help platforms create healthier online environments while maintaining engagement.
