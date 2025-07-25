# Multi-Disease Prediction (Bangla) - ML Project

## Overview

This repository implements a bilingual, ML-driven diagnostic framework for predicting diseases from symptoms. It focuses on the Bangla-speaking healthcare landscape — an underserved demographic in AI-driven health informatics.

## Key Features

- Dual-model system: Naive Bayes + MLP.
- Tailored for Bangla datasets and context.
- High accuracy: MLP with 99.34% Top-1, 100% Top-3.
- Interpretable outputs with ranked disease predictions (Top-K).
- Fully documented and modular Jupyter Notebook.

## Repository Structure

```
├── Multi_Disease_Prediction_Bangla_ML.ipynb   # Jupyter Notebook
├── requirements.txt                           # Dependencies
└── README.md                                   # Documentation
```

## Technology Stack

| Tool/Library   | Purpose                        |
|----------------|--------------------------------|
| Python 3.x     | Core language                 |
| Pandas         | Data manipulation             |
| NumPy          | Numerical operations          |
| Matplotlib     | Data visualization            |
| Scikit-learn   | Naive Bayes, metrics          |
| TensorFlow     | MLP model implementation      |

## Models Used

### Naive Bayes Classifier
- Probabilistic, interpretable, and fast.
- Best suited for baseline comparisons and low-resource deployment.
- Top-1 Accuracy: 97.37%.

### Multi-Layer Perceptron (MLP)
- Implemented with TensorFlow/Keras.
- Two hidden layers, ReLU activations.
- Captures non-linear symptom interactions.
- Top-1 Accuracy: 99.34%, Top-3: 100%.

## How to Run

### Prerequisites

Install all dependencies from `requirements.txt`:

```bash
pip install -r requirements.txt
```

### Running the Notebook

```bash
jupyter notebook
```

Open the `.ipynb` file and run cells in sequence.

## Evaluation Metrics

- Top-1 Accuracy
- Top-3 Accuracy (Top-K Ranking)
- Precision (Macro, Micro)
- Recall (Macro, Micro)
- F1-Score

## Dataset

- Bangla Disease Symptom Dataset
- Source: Mendeley Data
- Format: Symptom-disease mappings, text-based input

## Future Enhancements

- Bangla NLP integration for symptom entry
- Streamlit-based web app for non-technical users
- Real-time mobile interface for field diagnostics

## License

This project is licensed under the Creative Commons (CC) licenses.

## Author

Developed by an Engineering Undergraduate interested in scalable healthcare AI. Feedback and contributions are welcome.

