# ATS-Resume-Quality-Checker-using-Python

## Brief Description
This script analyzes the quality of a resume by extracting text from a PDF file and comparing it to a dictionary of industrial and system engineering key terms by area.

## Table of Contents
- [Built With](#built-with)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Features](#features)
- [Algorithm](#algorithm)
- [Data](#data)
- [Disclaimer](#disclaimer)
- [Feedback](#feedback)
- [Installation](#installation)
- [Contribution](#contribution)
- [Author](#author)
- [License](#license)

## Built With
List of libraries, frameworks, or tools used in the project:
- PyPDF2
- textract

## Prerequisites
Required software or tools to use or run the project:
- Python 3.x

## Getting Started
Instructions to download or clone the repository:
- Clone the repository using `git clone <repository-url>`.

Steps to install the required dependencies:
- Install the required libraries:
```
pip install PyPDF2 pip install textract
```

## Usage
Instructions or guidelines to use the project or tool:
- Run the script:
```
python resume_quality_report.py
```

Description of different features or functionalities:
- The script extracts text from a PDF file and compares it to a dictionary of industrial and system engineering key terms by area.
- The script calculates the score for each area by counting the number of key terms found in the text.
- The script creates a pie chart visualization of the results and saves it as a .png file.

## Features
List of different features or functionalities available in the project:
- Text extraction from PDF files.
- Text preprocessing (converting all strings to lowercase, removing numbers and punctuation).
- Comparison of text to a dictionary of industrial and system engineering key terms by area.
- Calculation of scores for each area.
- Creation of pie chart visualization of results.

## Algorithm
Description of the algorithm or model used in the project:
The script uses libraries such as PyPDF2 and textract to extract text from a PDF file. The text is preprocessed by converting all strings to lowercase, removing numbers and punctuation. The script includes a dictionary of industrial and system engineering key terms by area. The score for each area is calculated by counting the number of key terms found in the text. A pie chart visualization of the results is created and saved as a .png file.

How the algorithm works:
1. The script extracts text from a PDF file using PyPDF2 and textract libraries.
2. The text is preprocessed by converting all strings to lowercase, removing numbers and punctuation.
3. The script compares the preprocessed text to a dictionary of industrial and system engineering key terms by area.
4. The score for each area is calculated by counting the number of key terms found in the text.
5. A pie chart visualization of the results is created and saved as a .png file.

## Data
Description of the data used in the project:
The data used in this project is a PDF file containing a resume.

How the data is collected or processed:
The data is collected by providing a path to a PDF file containing a resume. The script extracts text from the PDF file using PyPDF2 and textract libraries.

## Disclaimer
A disclaimer to inform users about the limitations or accuracy of the project results:
The results provided by this script are not guaranteed to be 100% accurate and should be used for informational purposes only.

## Feedback
Instructions or guidelines to provide feedback about the project:
Please provide feedback about this project by opening an issue on GitHub.

## Installation
Steps to install the project or tool:
1. Clone the repository using `git clone <repository-url>`.
2. Install the required dependencies using `pip install -r requirements.txt`.

Dependencies or system requirements:
- Python 3.x

## Contribution
Guidelines to contribute to the project:
If you would like to contribute to this project, please feel free to submit a pull request or open an issue.

## Author
Name of the author or authors: **ARYAN BAJAJ**

## License
Type of license used for the project: MIT License
