# digital-forensics-labs
# Digital Forensics & Incident Response Labs

This repository contains hands-on digital forensics and incident response (DFIR) labs completed as part of university coursework.

The labs focus on forensic data acquisition, analysis of digital artifacts, hashing, file system investigation, and evidence handling using industry-relevant tools and techniques.

---

## 🔍 Skills Demonstrated
- Digital forensics methodology
- Evidence preservation & integrity verification
- Hashing (MD5, SHA1, SHA256)
- File type identification & carving
- Metadata analysis (EXIF)
- Entropy analysis
- Android & Windows forensic artifacts
- Linux command-line forensic tools
- Report writing & forensic documentation

---

## 🧪 Labs Included

### 🔹 Lab 1 – File Analysis & Forensic Fundamentals
- File type identification
- Text and pattern searching
- Hash comparison and integrity checks
- Metadata extraction
- Entropy analysis
- Introduction to forensic datasets

📁 Folder: `lab-1/`

---

### 🔹 Lab 2 – Advanced Digital & Mobile Forensics
- Android filesystem analysis
- Logical vs physical acquisition
- SQLite database analysis
- Application artifacts (browser, messaging apps)
- Disk forensics (MFT, partitions)
- Timeline reconstruction
- Forensic soundness evaluation

📁 Folder: `lab-2/`

---

## ⚠️ Disclaimer
All data used in these labs is **synthetic or provided for educational purposes only**.  
No real personal, organizational, or confidential data is included.

---

## 📫 Author
Samir Hossain Santo Bepu  
Cybersecurity | DFIR | Digital Forensics


# DIFO 2023 – Lab 1: File Analysis & Forensic Fundamentals

This lab focuses on foundational digital forensics techniques applied to a forensic dataset containing mixed and unknown file types.

---

## 🎯 Objectives
- Identify unknown file types
- Search for hidden or encoded text
- Verify file integrity using cryptographic hashes
- Extract metadata from image files
- Analyze entropy to detect encryption or compression

---

## 🛠️ Tools & Techniques
- `file`
- `grep`
- `sha1sum`, `md5sum`, `sha256sum`
- `exiftool`
- `binwalk`
- Entropy analysis
- Linux command-line environment

---

## 🔍 Key Tasks Performed
- Classified binary files based on magic numbers
- Identified duplicate files using hash comparison
- Extracted GPS metadata from image files
- Detected encrypted ZIP and PDF files
- Performed password recovery on protected files
- Identified steganography content in images

---

## 📄 Report
📎 **DIFO_2023_Lab-1_Report.pdf**  
Contains full methodology, commands used, outputs, and analysis.

---

## 📚 Skills Gained
- Practical forensic analysis workflow
- Evidence integrity verification
- File system artifact recognition
- Structured forensic reporting




