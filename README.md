# PDF-OCR-Table-Extraction

This code extracts tables and text from specified pages of PDF files and saves them into an Excel file. It uses the pdfplumber library to extract tables as DataFrames. If no tables are found, the pytesseract OCR tool is used to extract text from the page images, using the pdf2image library to convert pages into images. The extracted data is saved into an Excel file, with each table or OCR result placed in a separate sheet named after the PDF file and page number. This process automates the extraction of structured and unstructured data from multiple PDFs.
