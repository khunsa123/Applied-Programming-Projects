# 📄 PDF Converter Desktop Application

## 📌 Overview
This desktop application allows users to convert **PDF files** into:
- **Word documents (.docx)**
- **Image formats (JPEG / PNG)**

It provides a **simple and user-friendly interface** for selecting input files, choosing output formats, and performing conversions efficiently.

---

## ✨ Features
- Convert PDF files to **Word documents (.docx)**
- Convert PDF files to **image files (JPEG / PNG)**
- Simple and intuitive **GUI interface**
- Supports **batch conversion** for PDF to image

---

## ⚙️ Prerequisites
Before running the application, ensure the following dependencies are installed:

### 🐍 Required Software
- Python 3.x
- Tkinter
- PyPDF2
- pdf2image
- Pandoc *(required for PDF → Word conversion)*
- docx2txt *(for Word text extraction)*

---

## 📦 Installation

Install Python dependencies using pip:

```bash
pip install tk PyPDF2 pdf2image docx2txt

---

Install **Pandoc** separately and ensure it is added to your system PATH.

---

## 🚀 Usage
1. Launch the application  
2. Click **"Browse"** to select the input PDF file  
3. Choose the desired output format (**Word** or **Image**)  
4. Click **"Convert"** to start the process  

### 📄 For Word Conversion:
- Specify the output file name and location  

### 🖼️ For Image Conversion:
- Select the output folder  

---

## 🧪 Example Workflow
1. Click **"Browse"** and select a PDF file  
2. Choose **"Word"** as the output format  
3. Click **"Convert"**  
4. Provide the output file name and location  
5. Click **"Save"**  

The application will convert the PDF into a Word document.

---

## ⚠️ Troubleshooting
- Ensure **Pandoc** is installed and added to system PATH  
- Verify all Python dependencies are installed correctly  
- If the application crashes, check for missing libraries or incorrect installation  

---

## 🙏 Acknowledgments
- Built using **Python** and **Tkinter** for GUI  
- PDF to Word conversion powered by **Pandoc**  
- PDF to image conversion using **pdf2image**  
- Word text extraction using **docx2txt**
