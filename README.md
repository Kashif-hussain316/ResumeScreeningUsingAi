# AI-powered Resume Screening and Ranking System: Streamline Your Hiring Process
A web-based application that leverages AI to screen and rank resumes based on job descriptions, making your hiring process efficient and effective.

# 🖼️ Preview
![image](https://github.com/user-attachments/assets/1277d71c-9f92-4be0-accc-1f52c75efd9c)



# 🚀 Features
* Resume Screening: Automatically screen resumes based on the provided job description.
* Candidate Ranking: Rank candidates using AI-powered algorithms for better hiring decisions.
* PDF Support: Upload resumes in PDF format for seamless processing.

# 🛠 Tech Stack
> Frontend
* Streamlit (for building interactive web applications)
> Backend
* Python (for server-side operations)
* PyPDF2 (for extracting text from PDF files)
* scikit-learn (for text processing and similarity calculations)

# 📂 Directory Structure
```
github.com/codewithshek/AI-powered-Resume-Screening-and-Ranking-System/
├── Readme.md
├── AI-powered-Resume-Screening-and-Ranking-System-PPT.pdf
└── Main.py
```
# 📌 Setup & Installation

1. Clone the Repository
```
git clone https://github.com/codewithshek/AI-powered-Resume-Screening-and-Ranking-System.git
cd AI-powered-Resume-Screening-and-Ranking-System
```
2. Install Dependencies
```
pip install -r requirements.txt
```
3. Run the Application
```
streamlit run Main.py
```
4. Access the Application
```
Open your browser and navigate to the generated custom URL like http://localhost:8501/ to start using the AI-powered resume screening tool.
```

# 📜 Key Functions

* extract_text_from_pdf(file): Extracts text from a given PDF file.
* rank_resumes(job_description, resumes): Ranks resumes based on the provided job description using cosine similarity.

# 💡 Future Enhancements
✅ Implement support for additional file formats (e.g., DOCX).

✅ Add advanced natural language processing (NLP) techniques for better resume analysis.

✅ Develop a mobile application for on-the-go resume screening and ranking.
