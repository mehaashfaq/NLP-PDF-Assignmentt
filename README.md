# NLP Project – PDF Text Processing

## About This Project
This project is about applying Natural Language Processing (NLP) techniques on a large PDF file. The main goal is to extract text from the PDF and then clean, process, and analyze it using Python.

---

## What I Did in This Project

I worked on a full NLP pipeline step by step:

### 1. PDF Reading
- Loaded a PDF file using Python
- Extracted text from all pages
- Checked total number of pages
- Printed some sample text to understand the data

---

### 2. Text Cleaning (Preprocessing)
To clean the text, I applied several steps:
- Converted everything to lowercase
- Removed numbers using regex
- Removed special characters using regex
- Removed extra spaces
- Removed punctuation
- Split text into individual words (tokenization)

---

### 3. Stop Words Removal
- Removed common stop words like "is", "the", "and"
- Counted how many stop words were removed
- Counted remaining useful words

---

### 4. Text Processing
- Applied stemming to reduce words to their root form
- Applied lemmatization to get meaningful base words

---

### 5. Feature Extraction

#### One Hot Encoding
- Converted words into binary format
- Displayed results in a table using pandas

#### TF-IDF
- Converted text into numerical values
- Found important words based on frequency and importance
- Displayed results in tabular form

---

### 6. Visualization
- Created a scatter plot using Plotly
- Plotted words against their TF-IDF scores

---

## Tools & Libraries Used
- Python
- PyMuPDF (fitz)
- NLTK
- Pandas
- Scikit-learn
- Plotly

---

## How to Run This Project
1. Install required libraries:
 pip install pymupdf nltk pandas scikit-learn plotly


2. Place the PDF file in the same folder as the code

3. Run the notebook step by step



## Outputs Included
This project includes outputs for:
- PDF reading
- Number of pages
- Sample text
- Regex cleaning
- Stop word removal count
- Stemming results
- Lemmatization results
- One Hot Encoding table
- TF-IDF table
- Plotly graph

---

## Dataset
I used a public domain PDF file (100+ pages) for this project.

---

## Conclusion
This project helped me understand how raw text from a PDF can be processed and converted into meaningful numerical data for analysis using NLP techniques.
