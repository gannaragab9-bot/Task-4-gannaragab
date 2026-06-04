# The Machine's Optic Nerve 

  A robust, efficient, and deterministic Computer Vision program built with Python. This application operates based on defined preprocessing pipelines and confidence guardrails to ensure precision, reliability, and structured visual communication.

## 📖 Overview

  The Machine's Optic Nerve is a console-based application designed to demonstrate the fundamentals of conditional logic, image processing, and Optical Character Recognition (OCR). By utilizing advanced text preprocessing techniques (grayscale conversion and noise reduction), it ensures a reliable text extraction experience within a defined scope of visual interactions.

## ✨ Features

  * Advanced Pre-processing Engine: Automatically handles variations in image lighting by converting text to grayscale and applying Gaussian blur filters.
  * Smart Text Recognition: Powered by Google's Tesseract OCR engine utilizing structured page segmentation modes for maximum extraction accuracy.
  * The 80% Confidence Filter: Provides a safe, strict threshold that automatically filters out false positives and low-confidence hallucinations.
  * Visual Confirmation: Generates an output image containing precise bounding boxes and text labels for real-time validation.

## 🛠️ Tech Stack

  * Language: Python 3.x
  * Libraries: OpenCV (`cv2`), PyTesseract, NumPy
  * Core Paradigm: Image Processing & Machine Perception Logic

## 🚀 Getting Started

### Prerequisites
  Make sure you have Python installed, along with the Tesseract-OCR engine binaries configured on your system path.

### Installation
  Install the required dependencies using pip:
```bash
pip install opencv-python pytesseract numpy
