# PDF Editor

A FastAPI-based PDF editor application for uploading, annotating, and modifying PDF files.

## Features

- Upload PDF files
- Add text annotations
- Add highlight annotations
- Edit and update annotations
- Download modified PDFs

## Installation

1. Clone the repository
```bash
git clone https://github.com/aramasamy2526-cmd/edit_pdf.git
cd edit_pdf
```

2. Create virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

## Usage

Run the application:
```bash
uvicorn app:app --reload
```

Then open http://localhost:8000 in your browser.

## Technologies

- FastAPI
- PyPDF
- ReportLab
- HTMLx

## Author

aramasamy2526-cmd
