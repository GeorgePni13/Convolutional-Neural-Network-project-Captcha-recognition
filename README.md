CAPTCHA Breaking with Convolutional Neural Networks (CNNs)

This repository contains the code and analysis from a second-year master’s project in the Machine Learning course. The project explores Convolutional Neural Networks (CNNs) to evaluate their effectiveness in recognizing distorted alphanumeric characters in CAPTCHA images.

The dataset consists of 1,039 CAPTCHA images, each containing five characters with common distortions such as blurring, lines, and character overlaps. After testing a baseline OCR model that performed poorly, two CNN-based models were developed:

A simple CNN trained to predict the entire CAPTCHA text at once.

An advanced CNN architecture that breaks down the prediction task into five separate sub-models, each specializing in identifying one character position.

The advanced model achieved the best results with over 75% accuracy, demonstrating the potential of tailored CNN approaches in handling complex image recognition tasks like CAPTCHA.

Although this CAPTCHA format is outdated and not used in modern security, this project serves as a valuable case study for CNN capabilities in image-based sequence recognition and has broader implications for optical character recognition and pattern detection.

## Keywords
- CNN  
- Machine Learning  
- Captcha
- Keras
- TensorFlow  
- R
