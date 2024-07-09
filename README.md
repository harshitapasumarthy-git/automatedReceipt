# automatedReceipt
This repository contains a project aimed at classifying receipts using a combination of Computer Vision, Natural Language Processing (NLP), and Machine Learning (ML) techniques. The goal is to accurately categorize receipts based on their content and visual features.

Introduction
* Classifying receipts is a common problem in various business applications, such as expense management and bookkeeping. This project leverages computer vision to extract visual features, NLP to process textual information, and ML techniques to classify the receipts into predefined categories.

Features
* Receipt image preprocessing
* Optical Character Recognition (OCR) for text extraction
* Text preprocessing and feature extraction
* Visual feature extraction from receipt images
* Receipt classification using ML models
* Evaluation and visualization of model performance

Technologies Used
* Python: Programming language
* OpenCV: Computer vision library
* Tesseract: OCR engine
* NLTK: Natural Language Toolkit for text processing
* Scikit-learn: Machine learning library
* TensorFlow: Deep learning framework
* Pandas: Data manipulation and analysis
* NumPy: Numerical computing
* Matplotlib: Data visualization
Pipeline Overview: 
* Image Preprocessing: Enhancing receipt images using techniques like grayscale conversion, thresholding, and noise reduction.
* Text Extraction: Using Tesseract OCR to extract text from receipt images.
* Text Preprocessing: Cleaning and tokenizing the extracted text.
* Feature Extraction: Extracting both visual features (e.g., edges, contours) and textual features (e.g., keywords, phrases).
* Model Training: Training ML models (e.g., SVM, Random Forest, Neural Networks) on the extracted features.
* Evaluation: Evaluating the model performance using metrics such as accuracy, precision, recall, and F1-score.
