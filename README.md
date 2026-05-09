# project-2

# Project Name:

## AI-Powered Document Intelligence System


# Project Summary

The AI-Powered Document Intelligence System is a machine learning and OCR-based application developed to automatically classify and process different types of documents such as invoices, receipts, and contracts. The system uses Optical Character Recognition (OCR) to extract text from uploaded document images and then applies Natural Language Processing (NLP) techniques for document classification and information extraction.

The project integrates TF-IDF vectorization with a Logistic Regression classifier to accurately identify document categories. A REST API was developed using FastAPI to provide endpoints for document classification, text extraction, and complete document processing.

The system is capable of:

* Extracting text from document images using Tesseract OCR
* Classifying documents into multiple categories
* Providing confidence scores for predictions
* Processing uploaded files through REST API endpoints
* Returning structured JSON responses

This project demonstrates practical implementation of:

* OCR (Optical Character Recognition)
* Machine Learning Classification
* NLP Text Vectorization
* REST API Development
* FastAPI Deployment

The system was designed as a production-ready document processing pipeline and can be extended for real-world business automation applications such as invoice management, receipt analysis, and contract processing. 

---

# Technologies Used

* Python
* FastAPI
* Scikit-learn
* Tesseract OCR
* PIL (Python Imaging Library)
* Logistic Regression
* TF-IDF Vectorizer
* Joblib
* Uvicorn


# Main Features

* OCR-based text extraction
* Document classification
* REST API integration
* Swagger API documentation
* JSON response generation
* Confidence score prediction
* Image upload support


# Document Categories

The classifier was trained to identify:

* Invoices
* Receipts
* Contracts 


# API Endpoints

| Endpoint    | Purpose                                             |
| ----------- | --------------------------------------------------- |
| `/classify` | Classify uploaded document                          |
| `/extract`  | Extract text and entities                           |
| `/process`  | Complete OCR + Classification + Extraction pipeline |
| `/docs`     | Interactive Swagger documentation                   |

---

# Objective of the Project

The main objective of this project is to automate document understanding and reduce manual document processing efforts using Artificial Intelligence and Machine Learning techniques. The system provides a scalable and efficient solution for intelligent document analysis.
















 
