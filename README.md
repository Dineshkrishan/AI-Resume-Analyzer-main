# AI-Resume-Analyzer-main
An AI-based Resume Screening System that automates the evaluation and analysis of resumes to streamline the hiring process. This system leverages Natural Language Processing (NLP) and Machine Learning techniques to extract, score, and match candidate profiles with job requirements, saving recruiters time and increasing the accuracy of shortlisting.

##🚀 Features##
📄 Resume Parsing: Extracts relevant details such as name, contact, skills, education, and work experience.

🧠 AI-based Skill Matching: Compares candidate skills with job descriptions using NLP techniques.

📊 Ranking System: Scores and ranks resumes based on relevance to job roles.

🔍 Keyword Matching: Identifies critical keywords from resumes and job descriptions.

📁 Multiple Formats Supported: Supports resume files in PDF, DOCX, and TXT formats.

##🛠️ Tech Stack##
Python

Scikit-learn

spaCy / NLTK

Flask or Streamlit (for web interface)

Pandas & NumPy

##📂 Folder Structure##
bash
Copy
Edit
AI-Resume-Analyzer-main/
│
├── app/                     # Application code (UI/backend)
├── models/                  # Trained ML models (if any)
├── data/                    # Sample resumes and job descriptions
├── utils/                   # Helper functions for parsing and analysis
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
💡 How It Works
Upload Resume: User uploads one or more resume files.

Input Job Description: Recruiter provides job description or required skill list.

Processing: System parses resume content, applies AI/NLP for skill extraction.

Scoring: Each resume is scored and ranked based on relevance.

Output: Display sorted list of resumes with match scores.

##📦 Installation##
bash
Copy
Edit
git clone https://github.com/Dineshkrishan/AI-Resume-Analyzer-main.git
cd AI-Resume-Analyzer-main
pip install -r requirements.txt
python app/main.py

##✅ Use Cases##
HR Resume Shortlisting

Job Portals / ATS Systems

Campus Recruitment

Freelance Profile Screening

##🤝 Contributions##
Contributions are welcome! Please fork the repository and submit a pull request.

##📄 License##
This project is licensed under the MIT License.
