# English Conversational Abstractive Summary Generation using Pretrained Transformer Models

This repository contains code and resources for generating abstractive summaries from conversational English text using state-of-the-art pretrained Transformer models, specifically T5 and mT5. The project utilizes the SAMSum dataset, which comprises approximately 16,000 messenger-like conversations with corresponding summaries.

## Overview

The objective of this project is to create concise and meaningful summaries from conversational English text, simulating real-life messenger conversations. Leveraging the power of pretrained Transformer models like T5 and mT5, the aim is to generate accurate and contextually relevant abstractive summaries that encapsulate the essence of these conversations.

### SAMSum Dataset

The SAMSum dataset contains conversations crafted by linguists familiar with English. These conversations mimic daily conversational styles, encompassing varying levels of formality, slang usage, emoticons, and typos. Each conversation in the dataset is paired with a summary annotated by linguists. 

## Features

- Utilizes T5 and mT5 pretrained Transformer models for generating abstractive summaries.
- Training and evaluation performed on the SAMSum dataset, comprising messenger-like conversations.
- Handles diversified conversational styles, including informal, semi-formal, and formal registers, along with slang words and emoticons.
- Allows experimentation with different Transformer architectures and fine-tuning strategies for improved summary generation.

## Requirements

- Python 3.x
- Transformers library (Hugging Face)
- SAMSum dataset

## Dataset Link 
- https://huggingface.co/datasets/samsum?row=6


