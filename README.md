# 🧾 Entity–PAN Extraction using Python

## 📘 Project Overview
This project automates the extraction of **entities (Organisation / Person / HUF)** and their corresponding **PAN numbers** from PDF files.  
It uses **Python**, **Regex**, and **PDF text extraction** to generate a structured dataset showing the relationship `PAN_Of` between an entity and its PAN.

This project was developed as part of **AI Assignment 1** for learning applications of text processing and data extraction using AI-assisted tools.

---

## 🧠 Key Features
- 🔍 Extracts text from complex **PDF documents** using `pdfplumber`.
- 🧩 Detects valid **PAN numbers** using regex pattern matching.
- 🧾 Maps each PAN to its respective **entity name**.
- 🧠 Classifies entities as:
  - **Organisation**
  - **Person**
  - **Person (HUF)**

