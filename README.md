# Plagiarism Detection Using Artificial Intelligence

## Overview

This project presents a web-based application designed to detect plagiarism in both textual and visual content using advanced computational techniques.
In addition to conventional text analysis, the system incorporates the capability to evaluate flowchart images, thereby enhancing overall detection accuracy.

---

## Features

* Text plagiarism detection using the Longest Common Subsequence (LCS) algorithm
* Image plagiarism detection using histogram matching techniques
* Web-based interface developed using Django
* Displays similarity percentage for analyzed content
* Supports uploading of source and suspicious files

---

## Working

1. Upload source files (corpus)
2. Upload suspicious file
3. System compares using LCS (text) and histogram (image)
4. Displays similarity percentage and result

## Technology Stack

* Python
* Django
* OpenCV
* NLTK
* NumPy
* MySQL

---

## Execution Instructions

```bash
pip install -r requirements.txt
python manage.py runserver
```

Access the application via:
http://127.0.0.1:8000/

---

## Results

* Achieved approximately 81.91% accuracy in image plagiarism detection

---

## System Modules

* User Authentication
* Source File Upload
* Suspicious File Upload
* Image Upload and Detection

---

## Future Enhancements

* Integration of OCR-based detection
* Detection of AI-generated content
* Support for rotated and modified image analysis
* Implementation of advanced deep learning models

---
