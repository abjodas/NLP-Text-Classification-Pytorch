
# NLP Text Classification using PyTorch

This project implements text classification using PyTorch and the AG News dataset. It covers the following aspects:

- **Tokenization & Vocabulary Building:** Tokenizes the text using basic English tokenizer and builds vocabulary from the dataset.
- **Embeddings & Positional Encoding:** Visualizes word embeddings and incorporates positional encoding to improve the model's understanding of word positions.
- **Transformer Architecture:** Implements a transformer encoder for text classification tasks. Includes detailed calculations for query (Q), key (K), and value (V) matrices, along with dot-product attention.
- **Data Loading & Preprocessing:** Efficient data loading and preprocessing using `torchtext` and `DataLoader`.
- **Visualization:** Visualizes word embeddings, attention heads, and t-SNE plots for better understanding of how words are represented in the model.

### Features:
- Word embeddings with `torch.nn.Embedding`
- Positional Encoding for sequence-based tasks
- Transformer encoder for text classification
- t-SNE and 3D embedding visualization
- AG News dataset integration
- Data batching and padding for consistent input sizes

### Installation:
To run the project, install the required dependencies:
```bash
pip install torchtext torch dash plotly
```

### Usage:
1. Clone the repository.
2. Run the notebook or script for text classification with PyTorch.
3. Visualize the embeddings and attention using the provided visualization functions.

### Future Work:
- Add more datasets and extend to other NLP tasks like Named Entity Recognition and Sentiment Analysis.
- Implement a full transformer-based classifier for large-scale datasets.
