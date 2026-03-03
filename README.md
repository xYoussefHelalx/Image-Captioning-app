# Image Captioning Web App
An AI-powered image captioning application that generates natural language descriptions for images,
Users can either upload an image or scrape all images from a website URL and automatically generate captions

## Features

Upload single image and generate caption

Scrape all images from a website URL

transformer-based image captioning model

Deep learning powered by PyTorch

Simple interactive UI using Gradio

Automated caption generation pipeline


## How It Works

The system follows this pipeline:

### Image Input

Upload image manually

OR provide a webpage URL to scrape images

### Image Processing

Extract images using BeautifulSoup and requests

Preprocess images for model inference

### Caption Generation

Use HuggingFace transformers

Pretrained vision-language model

Generate natural language captions

### Display Output

Captions shown in Gradio interface

## Tech Stack

Python

PyTorch

HuggingFace Transformers

BeautifulSoup (bs4)

Requests

Gradio
