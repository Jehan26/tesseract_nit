# Handwritten Text OCR Conversion

This project performs Optical Character Recognition (OCR) on handwritten notes using Tesseract OCR, with preprocessing steps to enhance accuracy and a GUI to display the recognized text.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [File Descriptions](#file-descriptions)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to convert handwritten text into digital text using OCR techniques. It involves preprocessing the image to enhance text visibility, performing OCR using Tesseract, correcting the recognized text, and displaying the results in a graphical user interface.

## Features

- Image preprocessing to improve OCR accuracy:
  - Noise reduction
  - Contrast enhancement
  - Adaptive thresholding
  - Morphological operations
- OCR using Tesseract with customizable settings
- Text cleanup and correction using advanced spell checkers
- GUI for displaying the recognized text

## Prerequisites

- Python 3.x
- OpenCV
- NumPy
- Pytesseract
- Matplotlib
- Tkinter
- SpellChecker
- Autocorrect

You can install the required Python packages using pip:

```bash
pip install opencv-python numpy pytesseract matplotlib tkinter spellchecker autocorrect
