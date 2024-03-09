# Text-Summarization-using-Transformers

This repository provides implementations and examples of text summarization using state-of-the-art models such as GPT-2, T5, Pegasus, and fine-tuning BART using the Hugging Face Transformers library.

## Overview
Text summarization is the task of condensing a piece of text into a shorter version while preserving its most important information and overall meaning. With the advancements in natural language processing (NLP) and the availability of large pre-trained models, text summarization has seen significant improvements in recent years.

This repository explores different approaches to text summarization, leveraging powerful models from the Hugging Face Transformers library:

### 1. GPT-2: 
A transformer-based language model capable of generating coherent text based on a given prompt. We utilize GPT-2 for abstractive text summarization.
### 2. T5 (Text-To-Text Transfer Transformer): 
A transformer model trained in a text-to-text manner, meaning it can perform various NLP tasks with a single architecture by converting the task into a text-to-text format. We fine-tune T5 for text summarization.
### 3. Pegasus: 
A transformer model specifically designed for abstractive text summarization tasks. We utilize Pegasus for summarizing longer documents.
### 4. BART (Bidirectional and Auto-Regressive Transformers): 
A transformer model that combines the benefits of auto-regressive and auto-encoding architectures, making it suitable for sequence-to-sequence tasks like text summarization. We fine-tune BART using Hugging Face's Trainer API for enhanced summarization performance.

## Fine-tuning BART
To fine-tune BART for text summarization, follow the instructions in the bart directory. This includes:

Preparing your dataset
Configuring the fine-tuning script
Fine-tuning BART on your dataset
Evaluating the fine-tuned model
