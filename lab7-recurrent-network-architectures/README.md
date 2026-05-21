# Lab 7: Recurrent Network Architectures

## Overview

This lab compares recurrent neural network architectures for text classification, including LSTM and GRU variants with different embedding strategies.

## Skills Demonstrated

- Text preprocessing and sequence modeling
- Embedding-based neural network workflows
- LSTM and GRU architecture comparison
- Confusion matrix and precision evaluation
- Preserving trained outputs for reproducible review

## Contents

| Path | Purpose |
| --- | --- |
| `lab7_recurrent_network_architectures.ipynb` | Main recurrent neural network notebook |
| `artifacts/models/` | Trained model weights, histories, and prediction outputs referenced by the notebook |

## Folder Structure

```text
lab7-recurrent-network-architectures/
|-- README.md
|-- lab7_recurrent_network_architectures.ipynb
`-- artifacts/
    `-- models/
        |-- RNN-GRU-25*.h5/.pkl
        |-- RNN-GRU-50*.h5/.pkl
        |-- RNN-LSTM-25*.h5/.pkl
        `-- RNN-LSTM-50*.h5/.pkl
```

## Data

The notebook references large external text and embedding files from a local data directory. Those source files are not committed because of size. The trained model artifacts are retained because the notebook can load them for review without retraining every model.

## Review Notes

This lab is a strong portfolio example for sequence modeling, architecture comparison, and practical handling of expensive model training outputs.
