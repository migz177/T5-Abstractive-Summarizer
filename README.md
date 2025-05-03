# T5-Abstractive-Summarizer

## Quick Access

```python
from transformers import AutoModelForSeq2SeqLM, AutoTokenizer

# Load the model and tokenizer
model_path = "migz117/T5-Abstractive"
model = AutoModelForSeq2SeqLM.from_pretrained(model_path).to(device)
tokenizer = AutoTokenizer.from_pretrained(model_path)
```

## About

This repository contains a fine-tuned T5 model for abstractive text summarization. The model is trained to generate concise summaries while preserving the main ideas of the original text.

## Live Demo

Check out the live demo at [sumtext.streamlit.app](https://sumtext.streamlit.app/)

## Model Info

- Based on Google's T5 architecture
- Fine-tuned specifically for abstractive summarization
- Available on Hugging Face: `migz117/T5-Abstractive`
