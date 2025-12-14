# Book Summary Genre Classifier

This project classifies text, such as book summaries, into relevant categories using a multilingual Transformer model.

## How It Works

1. **Transformer Model** – Converts each text summary into an embedding vector that captures its meaning.
2. **Category Array** – Each category is also converted into an embedding for comparison with the text.
3. **Cosine Similarity** – Computes the similarity between the text and all categories.
4. **Top-K Selection** – Returns the most relevant categories for each text.
5. **Dynamic Function** – Accepts arrays of texts and categories, returning the best matching categories for each input automatically.

## Web Interface

A **simple web interface** is included using **Gradio**, allowing users to input summaries in real time and receive predicted categories. Similar interfaces can also be implemented with **Streamlit** or **Flask**.

## Requirements

```bash
pip install sentence-transformers
pip install gradio

