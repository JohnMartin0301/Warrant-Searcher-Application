# Warrant Searcher Application

## Overview
The Warrant Searcher Application is a powerful tool developed using Python, and is designed to help users search for specific warrant-related information within a collection of PDF, Scanned PDF, and Word documents. The application utilizes OCR (Optical Character Recognition) to scan documents for specific keywords and extracts relevant information.

## Features
- **Document Search** : Search for warrants based on criteria such as Case Number, Nature of Case, Name of Court, Subject/Accused, and Address/Location.
- **OCR Integration** : Uses Tesseract OCR to extract text from scanned images within PDF files.
- **Password Protection** : Ensures only authorized users can view, add, edit, or delete warrant information.
- **Multi-Platform Support** : Works on Windows, macOS, and Linux.
- **GUI Interface** : User-friendly interface built with Tkinter for ease of use.
- **Executable File** : The application has been converted to an .exe file for easy installation and use on Windows systems.

## How It Works
### 1. Set Up Password
![image](https://github.com/user-attachments/assets/c8886027-0548-4837-81a0-04eb7a3a5cfb)

![image](https://github.com/user-attachments/assets/d3d3aab8-0682-4d73-be94-634b30a7a300)

- On the first run, you will be prompted to create a password.
- This password will be required to access the main interface and manage documents.

### 2. Search Warrants
![image](https://github.com/user-attachments/assets/38b51696-aa8d-434f-a102-f0b3d31c7642)

![image](https://github.com/user-attachments/assets/6c6332c8-f947-4008-b8be-4da16a818e7c)

- Enter search criteria in the respective fields and click "Search Warrant".
- The application will search through all PDF and Word documents in the 'warrants' directory for matches.

### 3. Manage Documents
- **View** : Open the document to view its contents.
- **Add/Edit Information** : Add or edit warrant information (only for Word documents).
- **Delete** : Delete the document after confirming the action.

## Functionality
- **OCR and Text Extraction** :
    - Uses Tesseract OCR to recognize text in scanned images within PDFs.
- **Search Logic** :
    - Searches for the presence of keywords in the extracted text. Matches case number, nature of case, court name, subject, and address.
- **Password Verification** :
    - Protects the application with a password stored in a text file. Prompts the user to enter the password for sensitive actions.  

## Source Code Availability

The source code for the Warrant Searcher Application is not available in this repository. This application was developed as an internship project. The source code is not being shared publicly to maintain the originality and confidentiality of the work.
