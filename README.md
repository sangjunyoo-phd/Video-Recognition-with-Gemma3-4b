# Video-Recognition-with-Gemma3-4b

This project demonstrates how to summarize video content using Gemma 3-4B Instruct, an open-source multimodal large language model developed by Google. The model processes both image and text inputs, enabling high-quality video understanding through frame-level analysis.

# What it does

* **Vision-Language Inference**
Generate natural language summaries from video frames using the Gemma 3-4B model.

* **Open-Source LLM Integration**
Utilizes Hugging Face’s image-text-to-text pipeline.

* **Frame Sampling Pipeline**
Extract timestamp and frames from video input and generates prompt.

* **Cloud Ready**
Developed in Google Colab environment and utilizes A100.

# Requirements
* Google Colab with GPU (recommended)
* transformers, torch, opencv-python, Pillow, numpy
