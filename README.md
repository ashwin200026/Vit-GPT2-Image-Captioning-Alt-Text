# Image Captioning with Vision Encoder-Decoder Model

This repository contains a simple yet powerful image captioning script using the Vision Encoder-Decoder model. The model is based on the Vision Transformer (ViT) for image feature extraction and the GPT-2 decoder for generating captions. The implementation uses the Hugging Face Transformers library for seamless integration.

## Getting Started

### Prerequisites

Make sure you have the required dependencies installed:

- `torch`
- `PIL`
- `transformers`
- `matplotlib`

Install dependencies using the following command:


pip install torch Pillow transformers matplotlib


Model Configuration
You can customize the model's behavior by modifying the parameters in image_captioning.py. Adjust parameters such as max_length and num_beams to control caption generation.


