# Web Scraper (Homework helper)

A versatile Python tool that automatically extracts and saves content from web pages and PDF files using URLs from a Word document.

<img width="1472" alt="WebScaper" src="https://github.com/user-attachments/assets/2a5da827-19db-4d52-8217-cecf3b3a2fd4" />

## Table of Contents
* [General Info](#general-information)
* [Features](#features)
* [Tools and Technologies](#tools-and-technologies)
* [Setup](#setup)
* [Usage](#usage)
* [Credits](#credits)

## General Information
This project provides an efficient solution for batch processing URLs stored in a Word document. It can extract text content from web pages and download/extract content from PDF files. The tool is particularly useful for researchers, content aggregators, or anyone needing to collect and organize information from multiple web sources automatically.

## Features
* **Word Document URL Extraction**: Automatically reads hyperlinks from a Word document
* **Web Content Scraping**: Extracts text content from web pages
* **PDF Handling**: 
  - Downloads PDF files from URLs
  - Extracts text content from downloaded PDFs
* **Error Handling**: 
  - Robust error handling for failed downloads or inaccessible URLs
  - Detailed error reporting in the output file
* **Flexible Output**: 
  - Saves all extracted content in a single text file
  - Maintains clear separation between different sources
* **User Control**: Allows users to specify custom names for output files

## Tools and Technologies
* **Python Libraries:**
  - python-docx (for Word document processing)
  - BeautifulSoup4 (for web scraping)
  - Requests (for HTTP requests)
  - PyPDF2 (for PDF text extraction)

* **Features:**
  - URL extraction from Word documents
  - Web content scraping
  - PDF downloading and text extraction
  - Error handling and reporting

## Setup

1. **Install Python:**
   - Install Python 3.x on your local machine
   - Download from [Python official website](https://www.python.org/)

2. **Install Required Modules:**
   ```bash
   pip install python-docx
   pip install beautifulsoup4
   pip install requests
   pip install PyPDF2
   ```

## Usage

1. **Prepare Your Input:**
   - Create a Word document containing the URLs you want to scrape
   - Save the document as "Links to scrape.docx"

2. **Run the Script:**
   ```bash
   python challenge.py
   ```

3. **Follow the Prompts:**
   - Enter a name for your output text file
   - For PDF URLs, enter names for the PDF files when prompted

4. **Check the Results:**
   - The script will create a text file with all extracted content
   - PDFs will be downloaded to your working directory
   - Check the console for any error messages or success notifications

## Additional Notes:
* Ensure you have a stable internet connection
* Some websites may block automated scraping
* PDF extraction quality depends on the PDF file format
* Large files may take longer to process

## Credits

Created by Vijay Shrivarshan Vijayaraja

---

<div align="center">
Made by Vijay Shrivarshan Vijayaraja
</div>
