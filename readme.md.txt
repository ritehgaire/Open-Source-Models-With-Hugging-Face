# Projects Using Hugging Face Transformer Models

This repository showcases a series of projects built using open-source models from [Hugging Face](https://huggingface.co/). All of these projects are based on Transformer architecture, demonstrating its versatility across various AI tasks, including text, vision, and audio processing.

## Projects Overview

### 1. **Text-to-Speech**
   - Model: `kakao-enterprise/vits-ljs`
   - Description: Converts a given text into realistic speech. This project explores the use of Transformer models for generating human-like audio output from text.
   - Libraries: `transformers`, `gradio`

### 2. **Object Detection**
   - Model: `Zigeng/SlimSAM-uniform-77`
   - Description: Utilizes the Segment Anything Model (SAM) to detect and segment objects in images with high accuracy. 
   - Libraries: `transformers`, `PIL`, `torch`

### 3. **Image Captioning**
   - Model: `Salesforce/blip-image-captioning-base`
   - Description: Automatically generates descriptive captions for images, either conditionally or unconditionally.
   - Libraries: `transformers`, `PIL`

### 4. **Visual Question Answering (VQA)**
   - Model: `Salesforce/blip-vqa-base`
   - Description: Answers questions related to the content of an image using natural language understanding.
   - Libraries: `transformers`, `PIL`

### 5. **Zero-Shot Image Classification**
   - Model: `openai/clip-vit-large-patch14`
   - Description: Classifies images without explicit training on specific labels using zero-shot learning. The model matches images to the most appropriate text descriptions.
   - Libraries: `transformers`, `PIL`, `torch`

### 6. **Depth Estimation**
   - Model: `Intel/dpt-hybrid-midas`
   - Description: Predicts the depth map of an image, providing insights into the 3D structure of a scene from a 2D image.
   - Libraries: `transformers`, `PIL`, `torch`

### 7. **Segmentation**
   - Model: `Zigeng/SlimSAM-uniform-77`
   - Description: Generates segmentation masks for objects in an image using the Segment Anything Model (SAM).
   - Libraries: `transformers`, `PIL`

### 8. **Image Retrieval**
   - Model: `Salesforce/blip-itm-base-coco`
   - Description: Retrieves relevant images based on a text description by matching the content between images and text.
   - Libraries: `transformers`, `PIL`

## Installation

To run these projects locally, ensure you have the required libraries installed:

```bash
pip install transformers
pip install torch
pip install PIL
