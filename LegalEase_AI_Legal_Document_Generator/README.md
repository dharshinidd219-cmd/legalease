# LegalEase – AI-Powered Legal Document Generator

## Overview
LegalEase is a student-friendly web application that helps users create structured legal-document drafts from a simple form. It supports Rental Agreements, Affidavits, NDAs and Employment Agreements.

> Educational prototype only. Generated documents are drafts and should be reviewed by a qualified legal professional before use.

## Technologies
- Python
- Flask
- SQLite
- HTML5, CSS3, JavaScript
- python-docx

## Features
1. Document type selection
2. Form-based data collection
3. Automatic document drafting
4. Preview page
5. Document history stored in SQLite
6. DOCX download
7. Responsive user interface

## Installation
```bash
python -m venv venv
# Windows:
venv\Scripts\activate
# Linux/macOS:
source venv/bin/activate
pip install -r requirements.txt
python app.py
```
Open `http://127.0.0.1:5000/`.

## Future AI Upgrade
A production version can connect an LLM to classify the user's request, ask missing questions, retrieve jurisdiction-specific clauses, detect inconsistent information, and explain clauses in plain language. Human/legal review should remain available.
