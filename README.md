# Project 4 - Image/Text Recognition (OCR)

DecodeLabs Industrial Training Kit (Batch 2026)

## Description
A basic OCR (Optical Character Recognition) pipeline using pytesseract,
following a Grayscale -> Blur -> Adaptive Threshold pre-processing flow,
with an 80% confidence filter (per project spec).

## Features
- Pre-trained OCR engine (Tesseract via pytesseract)
- Image pre-processing: Grayscale, Gaussian Blur, Adaptive Thresholding
- 80% minimum confidence threshold on detected text
- Visual output with bounding boxes + confidence labels

## Sample Result
Detected text: "DECODELABS AI PROJECT 4 OCR RECOGNITION TEST"
All words recognized with 91-96% confidence.

## How to Run
!apt-get install -y tesseract-ocr
!pip install pytesseract opencv-python-headless
python ocr_text_recognition.py
