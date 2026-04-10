# 🖼️ HEIC to JPG Converter (PyQt5 Desktop App)

## 📌 Overview
This is a **desktop application built with PyQt5** that converts `.HEIC` image files into `.JPG` format in batch mode. It provides a simple GUI for selecting folders, tracking conversion progress, and optionally deleting original files after conversion.

---

## 🚀 Features
### 📁 File Conversion
* Batch convert `.HEIC` images to `.JPG`
* Automatically skips already converted files
* Maintains original image quality
### 🖥️ User Interface
* Simple and modern PyQt5 GUI
* Folder selection for input and output
* Progress bar for real-time conversion status
* Live log console for conversion feedback
### ⚙️ Extra Options
* Delete original HEIC files after conversion (optional)
* Auto-open output folder after conversion
* Default folders auto-created on first run

---

## 🧠 Tech Stack
* Python 3
* PyQt5 (GUI framework)
* Pillow (image processing)
* pillow-heif (HEIC decoding)

---

## 📁 Project Structure
```
project/
├── main.py              # Main application file
├── icon.icns           # App icon (macOS)
├── HEIC/               # Default input folder
├── JPG/                # Default output folder
└── README.md
```

---

## ⚙️ Installation & Setup
### 1. Clone the repository
```bash
git clone https://github.com/chwankai/HEIC-Converter.git
cd heic-to-jpg-converter
```
### 2. Install dependencies
```bash
pip install pyqt5 pillow pillow-heif
```
### 3. Run the application
```bash
python main.py
```

---

## 🖱️ How to Use
1. Launch the application
2. Select input folder containing `.HEIC` images
3. Select output folder for `.JPG` files
4. (Optional) Enable:

   * Delete original files
   * Open output folder after conversion
5. Click **Start Conversion**

---

## ⚠️ Notes
* Supports `.HEIC` format only
* Best used on macOS or Windows with proper HEIC support libraries
* Large batch conversions may take time depending on image size

---

## 📚 Conclusion
This project demonstrates a **GUI-based batch image conversion tool** using Python and PyQt5, combining multithreading, file handling, and image processing into a user-friendly desktop application.
