# Dynamic Multilingual XML Texts with QR Access via Python

## 📚 Master's Thesis Project

**Program:** Master's in Computational Linguistics and Internet Technologies in the Humanities  
**Title:** *A Multilingual Language Database of Short Functional Texts with XML Structure and Dynamic Access via Python and QR Code*

---

## 🧩 Project Overview

This project presents a multilingual collection of short functional texts (e.g. instructions, signs, notices), structured using **XML** and made dynamically accessible through **Python scripts** and **QR code integration**. The goal is to facilitate easy multilingual data retrieval, linguistic annotation, and digital access for educational, research, or applied use.

---

## 📁 Repository Structure
thesis-functional-texts/
├── data/ # XML files with multilingual texts
│ ├── bg/ # Bulgarian texts
│ ├── en/ # English texts
│ └── ... # Other languages
│
├── schema/ # XML Schema (XSD) to validate structure
│ └── text-schema.xsd
│
├── qr/ # Generated QR codes (PNG)
│ ├── bg/
│ ├── en/
│ └── ...
│
├── scripts/ # Python scripts
│ ├── generate_qr.py # Generates QR codes from XML texts
│ ├── xml_reader.py # Parses and displays XML contents
│ └── web_server.py # (Optional) Flask app for browsing
│
├── thesis/ # Thesis document files
│ ├── final.pdf # Final submitted version
│ └── references.bib # (If using LaTeX)
│
├── docs/ # Usage guides and documentation
│ └── usage.md
│
├── requirements.txt # Python dependencies
├── .gitignore # Git ignore rules
└── README.md # Project description (this file)
