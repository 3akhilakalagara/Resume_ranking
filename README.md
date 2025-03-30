## AI Resume Screening & Ranking System

## Overview
This project is a Streamlit-based web application that allows users to upload resumes in PDF format and ranks them based on a given job description using AI-driven text similarity.

## Features
- Upload multiple resumes in PDF format.
- Extracts text from the PDFs.
- Uses TF-IDF and Cosine Similarity to rank resumes against the job description.
- Displays ranked resumes with similarity scores.

## Technologies Used
- Python
- Streamlit
- PyPDF2
- scikit-learn
- Pandas

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repo.git
   ```
2. Navigate to the project directory:
   ```sh
   cd your-repo
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Run the Streamlit application:
   ```sh
   streamlit run app.py
   ```
2. Enter the job description.
3. Upload resumes in PDF format.
4. View ranked resumes based on similarity scores.
