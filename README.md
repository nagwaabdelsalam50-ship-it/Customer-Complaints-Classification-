# Customer Complaint Classification Using NLP

An NLP-based deep learning project that automatically classifies customer complaints into five categories.

## Models
- SimpleRNN
- LSTM
- GRU
- Fine-tuned DistilBERT

## Dataset
124,300 cleaned customer complaints across five categories.

## Results

| Model | Accuracy | Macro F1 |
|---|---|---|
| SimpleRNN | 69.26% | 68.75% |
| LSTM | 82.83% | 81.37% |
| GRU | 82.24% | 81.60% |
| **DistilBERT** | **86.16%** | **85.01%** |

## Deployment
An interactive Gradio application allows users to enter complaint text and receive a predicted category with a confidence score.

## Technologies
Python, TensorFlow, PyTorch, Hugging Face Transformers, Scikit-learn, Gradio.
