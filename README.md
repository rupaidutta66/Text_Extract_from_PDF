# Text_Extract_from_PDF

Text Data extraction from various PDf files consisting complex table data forms

# PDF Text Data Extraction Application

This Python application allows you to extract text data from a collection of PDF files containing complex table data forms. It utilizes the power of the `pdfplumber` library to parse and extract information from PDFs.

This Python application is a powerful tool designed to extract structured text data from a diverse range of PDF files, even those containing complex table data forms. Leveraging a combination of cutting-edge libraries and tools such as PaddleOCR, Tesseract OCR, NanoNet OCR, pdf2image, OpenCV, and Poppler Utils, this application ensures accurate and efficient extraction of valuable information from PDF documents.

## Overview

Robust OCR Integration: The application seamlessly integrates multiple OCR engines, including PaddleOCR, Tesseract OCR, and NanoNet OCR, to ensure accurate text recognition across a wide range of document layouts and languages.

Complex Table Data Extraction: With the power of OpenCV and advanced image processing techniques, the application is capable of identifying and extracting structured table data from PDF files, even when dealing with intricate table layouts.

Versatile PDF Conversion: The integration of pdf2image and Poppler Utils allows the application to convert PDF pages into high-quality images, ensuring precise OCR analysis and maximizing text extraction accuracy.

Configurable Settings: The config.json file enables you to fine-tune extraction settings, including OCR engine selection, image preprocessing parameters, and output formatting preferences, to best suit your specific use case.

Flexible Output Formats: Extracted data can be saved in a variety of structured output formats such as CSV, Excel, and JSON, facilitating easy integration with other data processing tools.

## Features

- Extracts structured text data from PDF files with complex table layouts.
- Handles various table formats and structures within the PDF documents.
- Outputs the extracted data in a structured format (e.g., CSV, Excel, JSON).

## Configuration

The config.json file allows you to customize various extraction parameters, including:
Selection of primary OCR engine (PaddleOCR, Tesseract OCR, NanoNet OCR).
Image preprocessing settings (resizing, enhancement, etc.).
Table detection and extraction preferences.
Output format selection (CSV, Excel, JSON).

## Acknowledgments

This application is built upon a stack of powerful libraries and tools, including PaddleOCR, Tesseract OCR, NanoNet OCR, pdf2image, OpenCV, and Poppler Utils. Each of these components contributes to the application's ability to accurately extract text data from complex PDF documents.
