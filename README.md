# NLP Assignment 2 — BBC Urdu NLP Pipeline

**GitHub Repository:** https://github.com/adnan05-gif/i25-7602-NLP-Assignment2

## Project Overview

This repository contains the implementation, experiments, evaluation
outputs, and visualizations for Natural Language Processing Assignment 2.

## Project Structure

- `notebooks/` — Main assignment implementation notebook.
- `data/` — BBC Urdu dataset and metadata.
- `part1_ppmi/` — PPMI analysis and visualizations.
- `part1_tfidf/` — TF-IDF representations and topic analysis.
- `part1_word2vec/` — Word2Vec training, embeddings, and evaluation.
- `part2_sequence_labelling/` — POS/NER annotation, BiLSTM experiments,
  ablations, and evaluation.
- `part3_transformer_topic_classification/` — Transformer and BiLSTM
  topic classification, evaluation, and attention visualizations.

## Reproduction Instructions

1. Open the main notebook in Google Colab.
2. Upload or mount the project data in the expected project directory.
3. Install any required Python packages listed in the notebook.
4. Execute the notebook cells in order to reproduce the relevant
   preprocessing, model, and evaluation steps.
5. Existing checkpoints and result files are included where applicable.

**Note:** Reproducing model training may require substantial compute time.
Existing saved results are included to document the completed experiments.

## Experimental Notes

Part 3 topic labels were inferred using category keywords and manual
title-level decisions. They are not original BBC gold-standard labels.
The evaluation results should therefore be interpreted with this
limitation in mind.

The corrected Transformer run is the final run used for reporting.
Obsolete debugging artifacts are excluded from the repository.

## Author

GitHub: [adnan05-gif](https://github.com/adnan05-gif/i25-7602-NLP-Assignment2)
