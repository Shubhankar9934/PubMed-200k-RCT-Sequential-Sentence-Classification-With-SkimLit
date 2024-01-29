# PubMed-200k-RCT-Sequential-Sentence-Classification-With-SkimLit


## Overview

This project explores a diverse array of deep learning models for sequential sentence classification in medical abstracts, using the PubMed 200k RCT dataset. Various architectures, including Conv1D and embeddings such as Universal Sentence Embedding and BERT, were employed to achieve accurate categorization of sentences into specific roles.

## Models and Achievements

- **NaiveBiase Model**: 72% Accuracy
- **Conv1D Model**: 78% Accuracy
- **Pretrained Token Embedding (Universal Sentence Embedding)**: 75% Accuracy
- **Conv1D Model using Character Level Embedding**: 73% Accuracy
- **Model with Both Token and Character Level Embedding**: 76% Accuracy
- **Model with Token, Character, and Position Level Embedding**: 81% Accuracy ([Paper Reference](https://arxiv.org/pdf/1612.05251.pdf))
- **Model with BERT Embedding**: 88% Accuracy

## Methodology and Future Work

- Diverse architectures were explored, showcasing the versatility of models for sentence classification.
- The BERT-based model demonstrated superior accuracy at 88%.
- Future work includes assessing model generalization and exploring ensemble methods for further improvements.

## Notebooks

- [NaiveBiase Model](https://github.com/Shubhankar9934/PubMed-200k-RCT-Sequential-Sentence-Classification-With-SkimLit/tree/main/Model%20Notebooks)
- [Conv1D Model](https://github.com/Shubhankar9934/PubMed-200k-RCT-Sequential-Sentence-Classification-With-SkimLit/tree/main/Model%20Notebooks)
- [Pretrained Token Embedding Model](https://github.com/Shubhankar9934/PubMed-200k-RCT-Sequential-Sentence-Classification-With-SkimLit/tree/main/Model%20Notebooks)
- [Conv1D Model with Character Level Embedding](https://github.com/Shubhankar9934/PubMed-200k-RCT-Sequential-Sentence-Classification-With-SkimLit/tree/main/Model%20Notebooks)
- [Model with Both Token and Character Level Embedding](https://github.com/Shubhankar9934/PubMed-200k-RCT-Sequential-Sentence-Classification-With-SkimLit/tree/main/Model%20Notebooks)
- [Model with Token, Character, and Position Level Embedding](https://github.com/Shubhankar9934/PubMed-200k-RCT-Sequential-Sentence-Classification-With-SkimLit/tree/main/Model%20Notebooks) ([Paper Reference](https://arxiv.org/pdf/1612.05251.pdf))
- [Model with BERT Embedding](https://github.com/Shubhankar9934/PubMed-200k-RCT-Sequential-Sentence-Classification-With-SkimLit/tree/main/Model%20Notebooks)

## Requirements

- Dependencies and resources needed for running the notebooks.

## How to Run

- Instructions on replicating the experiments and running the notebooks.

## Acknowledgments

- Appreciation to the original authors of the "PubMed 200k RCT" paper for dataset creation and inspiration.
