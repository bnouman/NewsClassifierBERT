# NewsClassifierBERT

# Problem Statement:
In an era of information overload, news consumers often struggle to efficiently find articles relevant to their interests or needs. Automatically categorizing news content into distinct topics can enhance content recommendation systems, improve information retrieval, and streamline digital media workflows. This project aims to build a news topic classification system that leverages the power of transformer-based language models, specifically BERT, to accurately classify news headlines into predefined topic categories. Using the AG News dataset, the model will be fine-tuned and evaluated using accuracy and F1-score, and deployed via a user-friendly interface (Streamlit or Gradio) for real-time interaction and demonstration of its capabilities.

This project fine-tunes a pre-trained BERT model (`bert-base-uncased`) using the AG News Dataset from Huggingface to classify news articles into one of four categories:

- World
- Sports
- Business
- Sci/Tech

The notebook performs tokenization, model training, evaluation using accuracy and F1-score, and can be extended for deployment using Gradio.

---

## Project Structure

```
.
├── ag news.ipynb        			# Jupyter notebook for model training and evaluation
├── README.md           			# Project overview and usage guide
└── Dataset new classifier BERT.rar/            # Folder for dataset (the dataset is compressed because it exceeds 25 MB of data)
```

## Model Details

- **Model**: `bert-base-uncased` (from Hugging Face Transformers)
- **Task**: Multi-class text classification
- **Frameworks**: PyTorch, Hugging Face Transformers, Datasets
- **Evaluation Metrics**: Accuracy, F1-score

---

## Installation

Install the required libraries:

```bash
pip install transformers datasets scikit-learn pandas matplotlib notebook
```

## Running the Notebook

You can run the notebook locally:

```bash
jupyter notebook "ag news.ipynb"
```

Or upload it to Google Colab and run it using a free GPU.

---

## Evaluation

The notebook evaluates the model using:

- **Accuracy**: Proportion of correct predictions
- **F1-score**: Harmonic mean of precision and recall

---

## Deployment

Deployment has been made already in the notebook file.

---

## Author

**Nouman Bashir**  
noumanbashir923@gmail.com  
www.linkedin.com/in/nouman-bashir
