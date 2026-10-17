# Article Relevance Search System

## Description

This project is the implementation of the paper "Implementasi Metode TF-IDF dan Cosine Similarity pada Sistem Pencarian Artikel yang Relevan".

It focuses on building an article search system that can measure the relevance of documents to a user query by using TF-IDF weighting and cosine similarity. The system is designed to help users find the most relevant articles based on textual similarity.

## Features

- Text preprocessing for article data
- TF-IDF vectorization
- Cosine similarity calculation
- Ranked article search results based on relevance
- Simple Python-based project structure for implementation and experimentation

## Requirements

- Python 3.10 or newer
- pip
- Internet access for installing dependencies (if required)

## Setup

Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/Scripts/activate
```

On Windows PowerShell, you can use:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

Then install the project dependencies:

```bash
pip install -r requirements.txt
```

If the project uses additional libraries, install them as needed:

```bash
pip install numpy pandas scikit-learn
```

## Run the Project

After the environment is activated and dependencies are installed, run the notebook or script to start the article search system

```bash
python app.py
```

## Project Structure

```text
.
├── README.md
├── requirements.txt
├── .venv/
├── src/
│   ├── app/
│   └── data/
└── ...
```

## Notes

This project is intended as an implementation of the paper mentioned above and can be extended for more advanced preprocessing, search optimization, or a web-based interface.
