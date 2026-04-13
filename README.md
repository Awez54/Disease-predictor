Disease Prediction and Medical Advisory System
Overview

This project is a backend-driven web application designed to predict diseases based on user-provided symptoms and generate structured medical insights. The system integrates machine learning, backend services, and AI-based content generation to provide a complete diagnostic workflow.

Features
Symptom-based disease prediction using a trained ML model
Backend API handling user inputs and processing requests
Integration with AI services for detailed medical insights
Specialist recommendation based on predicted condition
Diet and lifestyle suggestions generation
Hospital recommendation system based on location
PDF report generation for diagnosis summary
System Architecture

The system follows a modular architecture combining multiple components:

Frontend (EJS): User input and result display
Backend (Node.js + Express): Request handling and API logic
ML Module (Python): Disease prediction using Decision Tree
AI Integration: Generates structured medical insights
Data Layer: CSV dataset for model training
Tech Stack
Backend: Node.js, Express.js
Frontend: EJS
Machine Learning: Python, Scikit-learn (Decision Tree)
AI Integration: Google Gemini API
Data Processing: Pandas, NumPy
PDF Generation: pdfkit
Version Control: Git
Project Workflow
User inputs symptoms through the web interface
Backend processes input and calls Python ML model
ML model predicts the disease
AI service generates detailed medical insights
Backend compiles results and renders output
Optional: Generate downloadable PDF report
Setup Instructions
Prerequisites
Node.js
Python 3.x
Installation
npm install
pip install pandas scikit-learn
Environment Setup

Create .env file:

gemini_api=YOUR_API_KEY
PORT=3000
Run the Application
node index.js

Open:

http://localhost:3000
Key Learning Outcomes
Backend system design and API development
Integration of Node.js with Python-based ML models
Handling real-world data processing workflows
Working with AI APIs for dynamic content generation
Building end-to-end data-driven applications
Future Improvements
Replace CSV with database integration
Improve model accuracy using advanced algorithms
Add authentication and user history tracking
Deploy system on cloud infrastructure
