# crnn-handwriting-recognizer
A hybrid CRNN and NLP-based post-correction framework for Optical Character Recognition (OCR).
CRNN Handwriting Recognizer (Version 3)

CRNN Handwriting Recognizer (Version 3)
📘 Project Overview

This project implements a Hybrid CRNN and NLP-Based Post-Correction Framework for Optical Character Recognition (OCR).
It combines the Convolutional Recurrent Neural Network (CRNN) for visual text recognition with a lightweight Natural Language Processing (NLP) module for error correction.
The system is designed to accurately recognize and refine handwritten or printed text images by correcting common OCR errors such as misread characters, missing punctuation, and grammatical inconsistencies.

🚀 Features

Uses CRNN architecture for high-accuracy text recognition

Integrates NLP post-correction for contextual and grammatical refinement

Works on printed and handwritten text

Provides improved accuracy compared to baseline OCR models

Optimized for CPU, MPS (macOS), and CUDA (GPU) environments

Supports lightweight inference for faster performance

⚙️ Technologies Used

Python 3.10+

PyTorch / TensorFlow for CRNN

OpenCV for image preprocessing

NLTK / SpaCy for language-based correction

Matplotlib / NumPy for visualization

🧠 How It Works

The user inputs a text image.

The system preprocesses the image (resizing, denoising, grayscale conversion).

The CRNN model recognizes the text sequence.

The NLP post-correction layer refines errors and ensures linguistic accuracy.

The final corrected text is displayed or saved.

📊 Model Evaluation
Metric	Before Correction	After Correction
Word Error Rate (WER)	0.1560	0.1453
Character Error Rate (CER)	0.0425	0.0394

🧰 Setup Instructions

Clone this repository and run the main script:

git clone https://github.com/<your-username>/crnn-handwriting-recognizer.git
cd crnn-handwriting-recognizer
python main_v3.py

📄 File Description

main_v3.py – The complete OCR code implementing CRNN recognition and NLP-based post-correction.

README.md – Documentation explaining the project purpose, architecture, and usage.

👨‍💻 Author

Aadit Mali
IT Engineering Student
Vishwakarma Institute of Information Technology, Pune
📧 aadit.22311883@viit.ac.in
