# Disease Prediction and Medical Advisory System

## Overview
This project is a backend-driven web application designed to predict diseases based on user-provided symptoms and generate structured medical insights. The system integrates machine learning, backend services, and AI-based content generation to provide a complete diagnostic workflow.

---

## Features
- Symptom-based disease prediction using a trained ML model  
- Backend API handling user inputs and processing requests  
- Integration with AI services for detailed medical insights  
- Specialist recommendation based on predicted condition  
- Diet and lifestyle suggestions generation  
- Hospital recommendation system based on location  
- PDF report generation for diagnosis summary  

---

## System Architecture
The system follows a modular architecture:

- Frontend (EJS) – User input and result display  
- Backend (Node.js + Express) – Request handling and API logic  
- ML Module (Python) – Disease prediction using Decision Tree  
- AI Integration – Generates structured medical insights  
- Data Layer – CSV dataset for model training  

---

## Tech Stack
- Backend: Node.js, Express.js  
- Frontend: EJS  
- Machine Learning: Python, Scikit-learn  
- AI Integration: Google Gemini API  
- Data Processing: Pandas, NumPy  
- PDF Generation: pdfkit  
- Version Control: Git  

---

## Project Workflow
1. User inputs symptoms through the web interface  
2. Backend processes input and calls Python ML model  
3. ML model predicts the disease  
4. AI service generates detailed medical insights  
5. Backend compiles results and renders output  
6. Optional: Generate downloadable PDF report  

---

## Setup Instructions

### Prerequisites
- Node.js  
- Python 3.x  

### Installation
```bash
npm install
pip install pandas scikit-learn
