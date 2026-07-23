# AI Resume Analyzer

AI Resume Analyzer is a Python-based application that evaluates a candidate's resume against a job description using Large Language Models (LLMs). The application extracts text from PDF and DOCX resumes, analyzes compatibility with the provided job requirements, and generates structured insights using the Groq API.

## Features

- Analyze resumes against job descriptions
- Extract text from PDF and DOCX files
- AI-powered compatibility analysis using Groq LLM
- Structured output using Pydantic models
- Prompt engineering for consistent and reliable responses
- Terminal-based interface for quick evaluation

## Tech Stack

### Programming Language
- Python

### Libraries & Tools
- Groq API
- Pydantic
- PyPDF
- python-docx
- python-dotenv
- uv

## Project Structure

```
AI-Resume-Analyzer/
│
├── main.py
├── resume_analyzer.py
├── pyproject.toml
├── uv.lock
├── README.md
├── .gitignore
└── .env (not included)
```

## Installation

### Clone the repository

```bash
git clone https://github.com/PushpakBagadia/AI-Resume-Analyzer.git
```

### Navigate to the project directory

```bash
cd AI-Resume-Analyzer
```

### Install dependencies

Using uv:

```bash
uv sync
```

Or using pip:

```bash
pip install -r requirements.txt
```

### Run the application

```bash
python main.py
```

or

```bash
uv run main.py
```

## How It Works

1. Upload or provide a resume in PDF or DOCX format.
2. Enter the target job description.
3. The application extracts the resume content.
4. The extracted text and job description are sent to the Groq LLM.
5. The model evaluates the resume and returns structured compatibility results.

## Future Enhancements

- Web-based user interface
- Support for multiple resumes
- Resume ranking system
- Skills gap analysis
- ATS score estimation
- Export reports as PDF

## Author

**Pushpak Kumar**

GitHub: https://github.com/PushpakBagadia
