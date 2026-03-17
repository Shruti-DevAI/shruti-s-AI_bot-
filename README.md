# shruti's-AI_bot 
A Chatbot who takes input and resolve query of the user and also helps is giving feedback 
# Llama 3.1 Chatbot

A simple chatbot powered by **Meta Llama 3.1 8B Instruct** using Hugging Face Inference API + Gradio.

Just a basic working bot — no fancy CSS, no heavy customization.

## Features

- Chat with Llama 3.1 8B Instruct
- Supports Enter key and Send button
- Runs in Google Colab or Hugging Face Spaces
- Very few dependencies

## Requirements

- Hugging Face account + **Inference API token** (free tier is enough for testing)
- Python 3.9+
- Libraries: `gradio`, `huggingface_hub`

## Quick Start (Colab or local)

1. Get your Hugging Face token:  
   https://huggingface.co/settings/tokens → Create new token (read access)

2. Open in Colab or run locally:

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/YOUR_NOTEBOOK_LINK_HERE)

   Or clone & run:

   # Option A - in code (not recommended for public repos)
HF_TOKEN = "hf_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"

# Option B - better (environment variable)
export HF_TOKEN="hf_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
Run the notebook / script → open the Gradio link
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
   cd YOUR-REPO-NAME
   pip install gradio huggingface_hub
