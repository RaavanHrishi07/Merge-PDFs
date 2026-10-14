# 📄 Merge PDFs — Python PDF Merger

A simple and lightweight Python project to **merge multiple PDF files into a single document** using PyPDF2. It supports appending PDFs and inserting one PDF into another at a specified page position.

## ✨ Features

- 📎 Merge multiple PDF files into one document.
- ➕ Append PDFs sequentially.
- 📑 Insert one PDF into another at a specified page position.
- 🐍 Built with Python.
- ⚡ Simple setup and easy to use.

## 🛠️ Tech Stack

- **Language:** Python
- **Library:** PyPDF2 1.26.0

## 📁 Project Structure

```text
Merge_pdfs/
├── merge_pdfs.py
├── requirements.txt
├── samplePdf1.pdf
├── samplePdf2.pdf
├── README.md
└── .gitignore
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/RaavanHrishi07/Merge-PDFs.git
cd Merge-PDFs
```

### 2. Install dependencies

Make sure Python is installed, then run:

```bash
python -m pip install -r requirements.txt
```

### 3. Run the project

```bash
python merge_pdfs.py
```

The script processes the two sample PDF files and generates:

- `mergedPdf.pdf` — PDFs merged by appending.
- `mergedPdf1.pdf` — PDFs merged using the insertion method.

The generated files are excluded from Git using `.gitignore`.

## ⚙️ How It Works

The project demonstrates two PDF merging methods:

1. **Appending:** Adds the second PDF after the first PDF.
2. **Inserting:** Inserts the second PDF at the specified page position in the first PDF.

You can modify `merge_pdfs.py` to use your own PDF files.

## 📌 Requirements

- Python 3
- PyPDF2 1.26.0

## 👨‍💻 Author

**RaavanHrishi07**

GitHub: [@RaavanHrishi07](https://github.com/RaavanHrishi07)

## 📜 License

This project is open source. A licence can be added if you choose to distribute it under a specific open-source licence.