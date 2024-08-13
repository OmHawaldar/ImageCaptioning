# **Image Captioning**

## Overview

This project implements a Generative AI-powered application for image captioning using the BLIP (Bootstrapping Language-Image Pre-training) model from Hugging Face's Transformers library. The application is designed to generate descriptive captions for images, leveraging state-of-the-art image-text models.
### Features
- **Image Captioning:** Automatically generate descriptive captions for images.
- **Pre-trained BLIP Model:** Utilizes BLIP, a model pre-trained on large-scale image-text pairs for accurate and coherent caption generation.
- **User-friendly Interface:** Simple interface to upload images and view generated captions.
- **Extendable:** Easily adaptable to other image-to-text tasks or different use cases.

# Installation
## Prerequisites

- Python 3.7+
- Git
- pip (Python package installer)

### Clone the Repository: 
    git clone https://github.com/OmHawaldar/ImageCaptioning
    cd image-captioning-blip

### Install Dependencies
    pip install -r requirements.txt

Download BLIP Model

BLIP is integrated directly via the Hugging Face Transformers library. The model will be automatically downloaded when first used.
Usage
Running the Application

To start the application:

bash

python app.py

Generating Captions

    Upload an image through the web interface.
    The application will generate and display a caption for the uploaded image.

Example

    Input: 
    Generated Caption: "A cat sitting on a windowsill looking outside."

Models and Training

This project uses the BLIP model from Hugging Face, which is pre-trained on large datasets of image-caption pairs. For more advanced use cases, fine-tuning the BLIP model on custom datasets is possible.
License

This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgments

    Hugging Face for the Transformers library and BLIP model.
    The open-source community for providing valuable tools and resources.

Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements, bug fixes, or new features.
Contact

For any inquiries or questions, please contact [your email address].
