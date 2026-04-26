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

  
## WEEK: 6 
  ## Image Preprocessing + Convolutional Neural Networks

  
#  Project Overview

This project combines **Image Preprocessing techniques** with a **Convolutional Neural Network (CNN)** to build an intelligent system for image understanding and classification. The main goal is to first clean and enhance input images using classical image processing methods and then apply a deep learning model to classify the processed data accurately.

The system is implemented using Python with OpenCV for image preprocessing and TensorFlow/Keras for building and training the CNN model on the MNIST dataset of handwritten digits.

---

#  Project Summary

### 1) Image Preprocessing Phase

In this phase, input images are improved to make them suitable for machine learning:

* Conversion to grayscale
* Noise removal using morphological operations:

  * Erosion
  * Dilation
  * Opening
  * Closing
* Deskewing (straightening tilted images)
* Perspective transformation for proper alignment

 Purpose: Image ko clean aur structured banana taake model easily features extract kar sake.

### 2) Deep Learning Phase (CNN Model)

A Convolutional Neural Network is designed and trained using MNIST dataset:

* Input images reshaped to 28×28×1
* Normalization (pixel values 0–1 range me)
* One-hot encoding of labels
* CNN architecture:

  * Convolution layers (feature extraction)
  * MaxPooling layers (dimension reduction)
  * Flatten layer
  * Dense layers (classification)
  * Dropout layer (overfitting control)
* Model compiled using Adam optimizer and categorical crossentropy loss
* Trained on training data and evaluated on test data


#  Final Output

* Model handwritten digits (0–9) accurately classify karta hai
* Preprocessing improve karta hai input image quality
* CNN automatically features learn karta hai without manual feature engineering
* Final accuracy test dataset par evaluate hoti hai



  
