# AI/ML Projects Refresher

This repository is a curated refresher of seven applied machine learning labs. The projects move from exploratory analysis and classical modeling into neural network architectures for tabular, image, and text data.

The repository has been organized for portfolio review: each lab folder includes the notebook, a focused README, any required included data, and generated artifacts only when they help reproduce or inspect the work.

## Project Index

| Lab | Topic | Primary Focus | Folder |
| --- | --- | --- | --- |
| 1 | Exploring Table Data | Data quality checks, exploratory analysis, feature interpretation | [lab1-exploring-table-data](./lab1-exploring-table-data) |
| 2 | Exploring Image Data | Image loading, visualization, preprocessing workflow | [lab2-exploring-image-data](./lab2-exploring-image-data) |
| 3 | Extending Logistic Regression | Custom logistic regression, optimization, model comparison | [lab3-extending-logistic-regression](./lab3-extending-logistic-regression) |
| 4 | Multi-Layer Perceptron | Neural network classification on census-style tabular data | [lab4-multi-layer-perceptron](./lab4-multi-layer-perceptron) |
| 5 | Wide and Deep Networks | Deep learning with mixed feature types and model architecture diagrams | [lab5-wide-and-deep-networks](./lab5-wide-and-deep-networks) |
| 6 | Convolutional Networks | CNN architecture experimentation for image classification | [lab6-convolutional-network-architectures](./lab6-convolutional-network-architectures) |
| 7 | Recurrent Networks | LSTM/GRU modeling for text classification | [lab7-recurrent-network-architectures](./lab7-recurrent-network-architectures) |

## Repository Structure

Each lab now uses the same review pattern:

```text
labX-topic-name/
|-- README.md
|-- labX_topic_name.ipynb
|-- data/          # Included datasets or compressed source data, when needed
`-- artifacts/     # Preserved generated outputs, when useful for review
```

Notebook checkpoint files, OS metadata, cache folders, and transient runtime outputs are intentionally excluded.

## Current Folder Map

```text
.
|-- README.md
|-- .gitignore
|-- lab1-exploring-table-data/
|   |-- README.md
|   |-- lab1_exploring_table_data.ipynb
|   `-- data/
|-- lab2-exploring-image-data/
|   |-- README.md
|   `-- lab2_exploring_image_data.ipynb
|-- lab3-extending-logistic-regression/
|   |-- README.md
|   |-- lab3_extending_logistic_regression.ipynb
|   `-- data/
|-- lab4-multi-layer-perceptron/
|   |-- README.md
|   |-- lab4_multi_layer_perceptron.ipynb
|   `-- data/
|-- lab5-wide-and-deep-networks/
|   |-- README.md
|   |-- lab5_wide_and_deep_networks.ipynb
|   |-- data/
|   `-- artifacts/
|-- lab6-convolutional-network-architectures/
|   |-- README.md
|   `-- lab6_convolutional_network_architectures.ipynb
`-- lab7-recurrent-network-architectures/
    |-- README.md
    |-- lab7_recurrent_network_architectures.ipynb
    `-- artifacts/
```

## Skills Demonstrated

- Exploratory data analysis with pandas, NumPy, Matplotlib, and Seaborn
- Data cleaning, feature encoding, and validation of modeling assumptions
- Classical supervised learning with scikit-learn-style workflows
- Neural network implementation and evaluation for tabular, image, and text data
- Model comparison using accuracy, confusion matrices, precision, and training history
- Practical notebook organization for reproducible review

## Reviewing the Work

Start with the README in each lab folder, then open the notebook listed in that README. Some labs depend on large public datasets that are documented but not fully committed to keep the repository reviewable.

For a quick employer review, Labs 3 through 7 best demonstrate modeling depth, while Labs 1 and 2 show exploratory workflow and data preparation fundamentals.
