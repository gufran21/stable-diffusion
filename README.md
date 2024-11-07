# Stable Diffusion - Text-to-Image and Inpainting
This project is an implementation of Stable Diffusion, a deep learning model for generating images from text descriptions. It also includes an inpainting feature to modify parts of an existing image based on given prompts, filling in areas while preserving the overall context. 

## Features
- Text-to-Image Generation: Generate high-quality images based on descriptive text prompts.
- Inpainting: Modify or replace parts of an image using a mask and text description.

## Setup
### Prerequisites
  - Download vocab.json and merges.txt from https://huggingface.co/stable-diffusion-v1-5/stable-diffusion-v1-5/tree/main/tokenizer and save them in the data folder
  - Download v1-5-pruned-emaonly.ckpt from https://huggingface.co/stable-diffusion-v1-5/stable-diffusion-v1-5/tree/main and save it in the data folder
  - Python 3.8 or higher
  - CUDA for GPU acceleration (optional but recommended)
  - Virtual Environment (recommended)
    
### Installation
  **1. Clone the Repository:**
  ```bash
     git clone https://github.com/yourusername/stable-diffusion-inpainting.git
     cd stable-diffusion-inpainting
  ```
  **2. Create and Activate Virtual Environment:**
  ```bash
     conda create -n estable-diffusion python=3.11
     conda activate stable-diffusion
  ```
  **3. Install Required Packages:**
  ```bash
     pip install -r requirements.txt
  ```

### Usage
open to demo.ipynb, try and experiment image generation and image inpainting.


## Acknowledgments
- https://huggingface.co/stable-diffusion-v1-5/stable-diffusion-v1-5
- https://github.com/hkproj/pytorch-stable-diffusion
