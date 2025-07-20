# Arabic-pos-tagging-on-conll-u-data
A pipeline for Arabic Part-of-Speech tagging using RNN and LSTM models on CoNLL-U formatted data, with NetworkX graph representation for visualizing word relationships and syntactic structures in Arabic text.  Built specifically for Arabic dialect processing (Egyptian, Levantine, Gulf, Maghrebi) 

# Overview
A comprehensive pipeline for Arabic Part-of-Speech (POS) tagging using RNN and LSTM models on CoNLL-U formatted data, with NetworkX graph visualization for representing word relationships and syntactic structures in Arabic text.

# Project Description
This project implements a complete Natural Language Processing pipeline specifically designed for Arabic text analysis. The system processes Arabic text using the Universal Dependencies Arabic-PADT dataset and creates interactive graph representations of linguistic relationships using NetworkX.

# Key Features
1- Arabic POS Tagging: State-of-the-art sequence labeling using RNN/LSTM models

2- CoNLL-U Data Processing: Native support for Universal Dependencies format

3- Graph Visualization: NetworkX-based representation of word relationships

4- Multi-dialect Support: Handles various Arabic dialects (Egyptian, Levantine, Gulf, Maghrebi)

5- Performance Optimization: Efficient processing for real-time article analysis

# Dataset Information
The project uses the QCRI Arabic POS Dialect Dataset containing:

1- Training Data: 6,075 sentences with comprehensive POS annotations

2- Validation Data: Development set for model tuning

3- Test Data: Evaluation dataset for performance measurement

# Tag Schema: Universal POS tags including social media-specific tags (hashtags, mentions, URLs, emoji)

# Data Structure
Each data sample contains:

1- Sentences: List of Arabic tokens

2- POS Tags: Corresponding Universal POS labels

3- Morphological Information: Detailed linguistic annotations

# Technical Implementation
## Architecture
1- Sequence Models: RNN and LSTM networks for sequential POS tagging

2- Input Processing: Token-level encoding with contextual embeddings

3- Output Layer: Multi-class classification for POS tag prediction

4- Graph Generation: NetworkX integration for syntactic relationship visualization

# Performance Metrics
Accuracy: Token-level and sentence-level accuracy measurement

F1-Score: Weighted and macro-averaged performance metrics

Processing Speed: Optimized for real-time article processing

