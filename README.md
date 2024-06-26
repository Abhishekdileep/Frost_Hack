# Low-Dose to High-Dose Image Conversion Using Deep Learning

## Project Description

This project utilizes deep learning models to enhance the quality of low-dose medical images to the quality of high-dose images. This is particularly important in medical imaging, like CT scans, where reducing the dose of radiation is beneficial for patient safety but maintaining image quality is crucial for accurate diagnosis. We use state-of-the-art convolutional neural networks (CNNs) that learn from pairs of low and high-dose images to predict high-dose quality images from new low-dose images.

## Features

- **Image Enhancement**: Converts low-dose medical images to high-dose quality.
- **Deep Learning Model**: Uses advanced CNN architectures optimized for image translation tasks.
- **Evaluation Metrics**: Includes scripts to evaluate model performance using metrics such as PSNR, SSIM, and MSE.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.8 or higher
- Pip package manager
- Access to a GPU for training and inference (recommended)

## Installation

To install the required packages, follow these steps:

```bash
git clone https://github.com/your-repo/low-to-high-dose.git
cd low-to-high-dose
pip install -r requirements.txt
