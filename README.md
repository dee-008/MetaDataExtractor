# Image Metadata and OCR Tool

This Python project provides a graphical user interface (GUI) for extracting metadata and text from images using the Tesseract OCR engine and Python's Pillow library. The tool allows users to browse and load images, view their EXIF metadata, and extract text using Optical Character Recognition (OCR). Additionally, numeric characters are filtered from the OCR text and displayed separately.

## Features

- **Extract EXIF Metadata**: Displays metadata (if available) embedded in images, such as camera details, creation date, and other properties.
- **OCR (Optical Character Recognition)**: Extracts text from the image using Tesseract.
- **Filter Numeric Data**: Extracts only numeric characters from the OCR text.
- **Simple GUI**: The application provides an easy-to-use graphical interface with a "Browse Image" button to load images.

## Prerequisites

- **Python 3.x**
- **Tesseract-OCR**: Install the Tesseract OCR engine on your system. You can download it from [here](https://github.com/tesseract-ocr/tesseract).
- **Pillow**: The Python Imaging Library (PIL) for opening images and handling EXIF data.
- **pytesseract**: A wrapper for Tesseract to access OCR capabilities from Python.
- **Tkinter**: Standard Python library for building GUIs.
- **ScrolledText**: Tkinter widget to handle scrollable text areas.

## Installation

1. **Install Tesseract-OCR**:
   - Download and install Tesseract from [this link](https://github.com/tesseract-ocr/tesseract).
   - After installation, set the `tesseract_cmd` path in the script to point to the Tesseract executable.

   ```python
   pytesseract.pytesseract.tesseract_cmd = "C:\\Program Files\\Tesseract-OCR\\tesseract.exe"
