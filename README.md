# Style_Transfer_using_GAN


# Style Transfer using GAN (CycleGAN)

## Overview
This project implements a CycleGAN for unpaired image-to-image translation between MRI T1 and T2 modalities. The model learns to translate images without paired datasets using cycle-consistency loss.

## Features
- Complete CycleGAN architecture (Generators & Discriminators)
- Custom training loop using TensorFlow GradientTape
- Instance Normalization and PatchGAN discriminator
- Data preprocessing with tf.data pipeline
- Evaluation using MAE, SSIM, PSNR
- Visualization of generated results and training progress

## Project Structure
- **notebook.ipynb** – Main project notebook
- **data/** – Training and test images
- **results/** – Generated outputs and GIFs
- **checkpoints/** – Saved models

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- ImageIO

## Instructions
1. Open `notebook.ipynb`
2. Run preprocessing
3. Train the CycleGAN
4. Generate results and evaluations

## Author
**Sai Krishna Simhadri**  
Machine Learning & AI Engineer  
Optum AI – UnitedHealth Group

## Program
upGrad x IIITB – Machine Learning & AI Program  
Capstone Project – September 2024
