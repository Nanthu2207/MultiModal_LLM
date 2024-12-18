## TransArt: A Multimodal Application for Vernacular Language Translation and Image Synthesis
To develop a web-based application that first translates text from Tamil to English and then uses the translated text to generate relevant images. This application aims to demonstrate the
seamless integration of language translation and creative AI to produce visual content from
textual descriptions.

---

## Skills take away From This Project
 
   * Deep Learning
   * Transformers
   * Hugging face models
   * LLM
   * Gradio/AWS

---

## Domain

     AIOPS

---
    
## Approach

1. **Model Selection:**

     *  Select a robust Tamil to English translation model from Hugging Face,
   such asfor example openai/whisper-large-v3.

     *  Choose a reliable text-to-image model, example like , Flux-RealismLora
   generate images from the translated text.

     *  Integrate a text generation model like  gpt-neo or googlegemini api for
   producing creative English text based on the translated input.

2. **Application Development:**
    
     *  Build the app using gradio or stremlit to handle translation and image generation requests.

3. **Integration and Testing:**
 
     *  Integrate the Hugging Face models using their APIs.

     *  Conduct thorough testing to ensure accurate translations and image relevance.

4. **Deployment:**
 
     *  Deployed on [Hugging Face Spaces](https://huggingface.co/spaces/Nanthu22/TransArt) for easy access.

---

## Try the App

Explore the **TransArt** app, deployed on Hugging Face Spaces. This app allows you to translate text and generate creative images.

[![Hugging Face Spaces](https://img.shields.io/badge/🤗-Hugging%20Face-orange)](https://huggingface.co/spaces/Nanthu22/TransArt)

Click  [here](https://huggingface.co/spaces/Nanthu22/TransArt) to try it out!


---

## Technology Used
1. **Deep Learning**
2. **Python**
3. **Large Language Models (LLMs)**
4. **Transformers**

---

## Packages and Libraries
```python
import torch
import gradio as gr
import tempfile
import os
from transformers import pipeline, GPTNeoForCausalLM, GPT2Tokenizer
import requests
from PIL import Image
import io
```

---


## Output

![IMG_20241216_225421 (1)](https://github.com/user-attachments/assets/1faea7b3-e426-4d9a-a5cc-7576c7a6196b)







