# 📄 PDF Converter Desktop Application

## 📌 Overview

A **Python desktop application** for converting PDF files into other formats. Built with Tkinter for the GUI, it supports conversion to Word documents (`.docx`) and image formats (JPEG/PNG), with a clean and intuitive interface.

---

## ✨ Features

- Convert PDF to **Word document (.docx)**
- Convert PDF to **image files (JPEG / PNG)**
- Simple and intuitive **GUI interface**
- Supports **batch conversion** for PDF to image

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **GUI:** Tkinter
- **PDF Processing:** PyPDF2, pdf2image
- **Word Conversion:** Pandoc
- **Word Text Extraction:** docx2txt

---

## ⚙️ Installation & Usage

```bash
# Install Python dependencies
pip install tk PyPDF2 pdf2image docx2txt
```

> **Note:** Install [Pandoc](https://pandoc.org/installing.html) separately and ensure it is added to your system PATH (required for PDF → Word conversion).

### ▶️ Run the Application

```bash
python app.py
```

1. Click **Browse** to select a PDF file
2. Choose output format: **Word** or **Image**
3. Click **Convert**
4. Specify output file name/location and save

---

## ⚠️ Troubleshooting

- Ensure **Pandoc** is installed and on your system PATH
- Verify all Python dependencies are installed correctly
- If the app crashes, check for missing libraries

---

## 📬 Contact

**Khunsa Iftikhar**
📧 [khunsaiftikhar123@gmail.com](mailto:khunsaiftikhar123@gmail.com)
🔗 [linkedin.com/in/khunsa-iftikhar](https://www.linkedin.com/in/khunsa-iftikhar/)
