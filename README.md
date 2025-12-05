# Visitor Pass Management System

The **Visitor Pass Management System** is a digital solution designed to automate visitor identity verification and streamline the pass-issuing workflow. Using OCR technology, the system extracts and validates information from government-issued IDs such as **Aadhaar (UIDAI)** and **PAN**, enabling faster and more reliable visitor processing.

---

## 🚀 Features

### 🔍 OCR-Based ID Extraction  
Automatically extracts text and key fields from Aadhaar and PAN cards using OCR technology.

### ✔️ Data Validation  
Validates extracted information to reduce manual errors and ensure accurate verification.

### 🎫 Automatic Pass Generation  
Generates a digital visitor pass after verification, reducing processing time.

### 🗂️ Structured Data Storage  
Stores all visitor details in a clean and searchable format for efficient backend operations.

### 🖥️ Simple and Clean UI  
Straightforward screens for upload, verification, and pass generation.

---

## 🖼️ Screenshots

> Replace the image paths with your actual file names.

### 1. Dashboard
![Dashboard](./screenshots/dashboard.png)

### 2. ID Upload & OCR Extraction
![OCR Extraction](./screenshots/ocr-extraction.png)

### 3. Data Validation Screen
![Validation](./screenshots/validation.png)

### 4. Visitor Pass Output
![Visitor Pass](./screenshots/visitor-pass.png)

---

## 🧩 Tech Stack

- **Backend:** Java, Spring Boot  
- **Frontend:** React (or HTML/CSS)  
- **OCR Engine:** Tesseract / EasyOCR / Google Vision (your choice)  
- **Database:** MySQL / PostgreSQL  
- **Build Tool:** Maven / Gradle

---

## 🔄 System Workflow

1. User uploads Aadhaar or PAN card image.  
2. OCR engine extracts all relevant data fields.  
3. System validates and formats the extracted data.  
4. Verified details are stored in the database.  
5. A visitor pass is generated and displayed to the user.

---

## 🎯 Purpose

This system provides a smarter alternative to manual visitor verification.  
It increases accuracy, reduces processing steps, and ensures a smooth, secure visitor-entry experience.

---
