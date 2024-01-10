# Capstone-3
# BizCardX : Extracting_Business_Card_Data_with_OCR
## Introduction:

  > BizCardX is a user-friendly tool designed to effortlessly extract information from business cards using Optical Character Recognition (OCR). The project utilizes the EasyOCR Python package, a simple yet powerful library for OCR, to recognize text on business cards with minimal effort.

## What is EasyOCR?

  EasyOCR is a Python package that streamlines the process of Optical Character Recognition for computer vision developers. Its ease of use is unparalleled:

   - Installation with a single pip command.
   - Minimal dependencies for a hassle-free configuration.
   - Only one import statement and two lines of code to perform OCR.

## Project Overview
 
   BizCardX is a user-friendly tool for extracting information from business cards. The tool uses OCR technology to recognize text on business cards and extracts the data into a SQL database after classification using regular expressions. Users can access the extracted information using a GUI built using streamlit.
   
   BizCardX offers a simple and intuitive user interface for extracting and managing business card information. Here's a brief overview:

  - Text Extraction: Utilizes EasyOCR to recognize and extract text from business card images.
  - Classification: Classifies extracted text into categories such as company name, cardholder name, designation, and more using regular expressions.
  - GUI Interface: A user-friendly interface built with Streamlit, guiding users through the process.
  - Database Integration: Stores extracted information in a MySQL database for easy access and management.
   
## Libraries/Modules used!

   - Pandas: Creates a DataFrame with the scraped data.
   - mysql.connector: Handles store and retrieve of data in MySQL.
   - Streamlit: Creates a Graphical user Interface for seamless user interaction.
   - EasyOCR: Extracts text from images, a crucial component for OCR
   
## Workflow
    
  1. Upload Business Card: Use the UPLOAD & EXTRACT menu to upload a business card image.
  2. Text Extraction: EasyOCR extracts text from the uploaded business card.
  3. Data Classification: Classify the extracted text into relevant categories such as company name, cardholder name, etc.
  4. Data Display: View the classified data and make edits if necessary.
  5. Database Upload: Click the "Upload to Database" button to store the data in a MySQL database.
    
## Database Operations

  The MODIFY menu provides options to READ, UPDATE, and DELETE data in the MySQL database.
