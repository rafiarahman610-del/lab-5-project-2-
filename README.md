# lab-5-project-2

## Receipt OCR Analyzer

Here’s a clear, presentation-ready explanation of a **Basic OCR (Optical Character Recognition) Project**—including overview, features, and working:

## 1. Project Overview

**OCR (Optical Character Recognition)** is a technology that converts text from images, scanned documents, or PDFs into editable and searchable digital text.

 A **basic OCR project** typically:

* Takes an image (e.g., scanned document, handwritten note)
* Detects text inside it
* Converts that text into machine-readable format (like a `.txt` file)

 Example:
You upload an image of a printed page → OCR extracts the text → you can copy/edit it.

## 2. Key Features

A simple OCR system usually includes:

###  Text Detection

* Identifies where text exists in the image

###  Text Recognition

* Converts detected text into actual characters (A–Z, numbers, symbols)

###  Multi-format Input

* Supports images like JPG, PNG, or scanned PDFs

###  Language Support

* Can recognize English (basic systems), sometimes multiple languages

###  Preprocessing

* Improves image quality (noise removal, grayscale conversion)

###  Output Options

* Displays extracted text on screen
* Saves text into files (TXT, PDF)


## 3. Working 

Here’s how a basic OCR system works:

###  Step 1: Image Input

* User uploads or scans an image

###  Step 2: Preprocessing

* Convert image to grayscale
* Remove noise
* Adjust brightness/contrast
* Binarization (black & white conversion)

 Purpose: Improve accuracy

### Step 3: Text Detection

* System finds regions where text is present
* Uses bounding boxes around text areas


###  Step 4: Character Recognition

* Each character is identified using pattern recognition or AI models
* Converts image pixels → actual letters


## 4. Tools & Technologies 


* Python
* OpenCV (image processing)
* Tesseract OCR engine
* PIL (Python Imaging Library)


##  5. Applications

* Digitizing books 
* License plate recognition 
* Bank cheque processing 
  
