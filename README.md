# Text-Analytics-Tool
This is a Python program designed to perform comprehensive text analysis on input data stored in an Excel file. The analysis includes keyword density calculation, content analysis with multiple metrics, sentence level analysis, and sentiment analysis.

[中文版](README.CN.md)

# Installation
Make sure Python is installed on your machine. This program was developed using Python 3.10, but it should work with any version newer than 3.6.

Clone this repository to your local machine.

Install the necessary Python packages using pip:

```
pip install nltk openpyxl textstat
```
Download the necessary NLTK data:

```
python -m nltk.downloader vader_lexicon punkt averaged_perceptron_tagger
```
# Usage
The program expects an Excel file with text data for analysis. Here is a simple usage example:

```
shell
python text_analytics_tool.py input.xlsx output.xlsx
```
This will read the input data from input.xlsx, perform the analysis, and write the results to output.xlsx.

# Contributing
We welcome contributions to this project. Please submit a pull request with your changes.
