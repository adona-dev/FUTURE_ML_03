# Resume / Candidate Screening System

## Overview

This project is a Machine Learning and Natural Language Processing (NLP) based Resume Screening System developed as part of **Future Interns - Machine Learning Internship (Task 3)**.

The system automatically analyzes resumes, compares them with a given job description, ranks candidates based on similarity, and identifies missing skills to assist recruiters during the initial screening process.

---

## Features

* Resume text cleaning and preprocessing
* Resume parsing
* Job description matching
* TF-IDF feature extraction
* Resume-to-job similarity scoring
* Candidate ranking
* Skill gap identification
* Candidate ranking visualization

---

## Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

## Dataset

**Resume Dataset (Kaggle)**

The dataset contains resumes from multiple job categories and is used to demonstrate resume screening and candidate ranking using NLP techniques.

---

## Workflow

1. Load the resume dataset
2. Clean and preprocess resume text
3. Create a job description
4. Convert text into TF-IDF vectors
5. Compute cosine similarity between resumes and the job description
6. Rank candidates based on similarity scores
7. Extract skills from resumes
8. Identify missing skills
9. Visualize candidate rankings

---

## Output

The project generates:

* Ranked candidate list
* Similarity scores
* Extracted skills
* Missing skills
* Resume category distribution chart
* Top ranked candidates chart

---

## Business Use Case

This system helps recruiters reduce manual effort by automatically comparing resumes with job requirements. It enables faster shortlisting of candidates, highlights missing skills, and supports more consistent hiring decisions.

---

## Future Improvements

* PDF resume parsing
* Advanced skill extraction using spaCy
* Transformer-based embeddings (BERT/Sentence Transformers)
* Web-based recruiter dashboard
* Support for multiple job descriptions

---

## Project Structure

```text
FUTURE_ML_03/
│
├── notebook/
│   ├── resume_screening.ipynb
│   └── ranked_candidates.csv
│
├── images/
│   ├── category_distribution.png
│   └── top_candidates.png
│
├── README.md
├── requirements.txt
└── .gitignore
```
