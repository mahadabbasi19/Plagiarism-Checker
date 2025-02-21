# Plagiarism-Checker
Welcome to the Plagiarism Checker project! This Python script helps you detect similarities between text documents, such as text files, DOCX files, and PDF files. This README will guide you through using the plagiarism checker and provide information on how to get started.

### Table of Contents
* About the Plagiarism Checker
* Getting Started
* Supported File Formats
* Usage
* Plagiarism Detection
* Contributing

### About the Plagiarism Checker
The Plagiarism Checker is a Python script designed to compare the text content of two documents and calculate a similarity percentage. It uses the RapidFuzz library to perform text comparison based on fuzzy matching. A high similarity percentage indicates potential plagiarism.

### Getting Started
To use the Plagiarism Checker, follow these steps:

Clone or download this repository to your local machine.

Make sure you have Python 3.x installed on your computer.

Install the required libraries using pip:

pip install python-docx PyPDF2 rapidfuzz

Run the plagiarism_checker.py script.

### Supported File Formats
The Plagiarism Checker supports the following file formats:

Text files (.txt): You can compare two plain text files for plagiarism.

Word documents (.docx): The script can analyze the content of DOCX files.

PDF files (.pdf): PDF files are also supported. The script extracts text from PDFs for comparison.

### Usage
To use the Plagiarism Checker, provide the names of the two files you want to compare, separated by a comma when prompted.
For example:

Enter Names of Two Files (Comma Separated): file1.txt, file2.txt

The script will then analyze the content of the specified files and provide a similarity percentage along with a plagiarism alert if the similarity is above a certain threshold (default is 70%).

### Plagiarism Detection
The Plagiarism Checker calculates a similarity ratio using the RapidFuzz library. If the similarity ratio is equal to or greater than 70%, a plagiarism alert is displayed. You can adjust this threshold in the code if needed.

### Contributing
We welcome contributions to this project. If you have ideas for improvements or bug fixes, please fork this repository, make your changes, and create a pull request. We appreciate your contributions!

If you have any questions or need further assistance, please don't hesitate to reach out.
Happy checking! 📝🔍
