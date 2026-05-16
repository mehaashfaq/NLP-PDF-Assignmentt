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
 <img width="590" height="367" alt="image" src="https://github.com/user-attachments/assets/2accdfe9-b2de-48ac-aaf9-fff788af55aa" />
<img width="402" height="338" alt="image" src="https://github.com/user-attachments/assets/d8397a6a-1684-4f52-8369-561a8235176b" />




---

### 2. Text Cleaning (Preprocessing)
To clean the text, I applied several steps:
- Converted everything to lowercase
- Removed numbers using regex
- Removed special characters using regex
- Removed extra spaces
- Removed punctuation
- Split text into individual words (tokenization)
<img width="397" height="284" alt="image" src="https://github.com/user-attachments/assets/58084922-eda6-446d-9572-470cffbce0b5" />

---

### 3. Stop Words Removal
- Removed common stop words like "is", "the", "and"
- Counted how many stop words were removed
- Counted remaining useful words

---

### 4. Text Processing
- Applied stemming to reduce words to their root form
- Applied lemmatization to get meaningful base words
<img width="680" height="146" alt="image" src="https://github.com/user-attachments/assets/2cf0ee30-9e90-4bbe-bbbc-a9f182158752" />


---

### 5. Feature Extraction

#### One Hot Encoding
- Converted words into binary format
- Displayed results in a table using pandas
<img width="435" height="340" alt="image" src="https://github.com/user-attachments/assets/effe9ed0-10e3-4c03-a5ba-c00316b599c4" />

#### TF-IDF
- Converted text into numerical values
- Found important words based on frequency and importance
- Displayed results in tabular form

  <img width="527" height="268" alt="image" src="https://github.com/user-attachments/assets/e004caa9-e01d-4507-bec2-abc91799051a" />


---

### 6. Visualization
- Created a scatter plot using Plotly
- Plotted words against their TF-IDF scores
<img width="471" height="274" alt="image" src="https://github.com/user-attachments/assets/c8ee50b9-e629-42c8-9cd1-300ce3112cb2" />

<img width="651" height="374" alt="image" src="https://github.com/user-attachments/assets/c6afbd50-924e-4666-b952-d804ea4edda2" />

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
