# 📄 Automated Resume Relevance Check System

An AI-powered Resume Screening and Candidate Evaluation Platform that automates the recruitment process by analyzing resumes against job descriptions using Natural Language Processing (NLP), Sentence Transformers, and Semantic Similarity Analysis.

The system helps recruiters quickly identify qualified candidates by generating relevance scores and automated hiring verdicts, reducing manual screening effort and improving recruitment efficiency.

---


## 🎯 Project Overview

The Automated Resume Relevance Check System is designed to streamline the resume screening process by automatically evaluating candidate resumes against specific job descriptions.

Instead of relying solely on keyword matching, the system uses advanced semantic similarity techniques to understand the contextual meaning of both resumes and job descriptions, resulting in more accurate candidate evaluations.

The platform provides two separate modules:

### 👨‍🎓 Student Dashboard

Candidates can:

- Upload resumes in PDF or DOCX format
- Paste job descriptions
- Receive an automated relevance score
- View hiring verdicts

### 👨‍💼 HR Dashboard

Recruiters can:

- View all candidate submissions
- Access evaluation scores
- Review candidate rankings
- Track recruitment records

---

## 🚀 Key Features

### 📂 Resume Upload and Parsing

Supports:

- PDF Resumes
- DOCX Resumes

Automatically extracts text from uploaded resumes for analysis.

---

### 📝 Job Description Analysis

Allows recruiters or candidates to provide job descriptions for evaluation.

The system uses the job description as the benchmark for matching candidate qualifications.

---

### 🤖 Semantic Similarity Analysis

Unlike traditional keyword matching systems, this project uses Sentence Transformers to understand the contextual meaning of resumes and job descriptions.

Benefits:

- Better candidate matching
- Reduced false positives
- Improved recruitment accuracy

---

### 📊 Automated Resume Scoring

The system calculates a relevance score using:

- Sentence Embeddings
- Cosine Similarity
- NLP-Based Semantic Matching

This score indicates how closely a resume aligns with the job requirements.

---

### ✅ Automated Verdict Generation

Based on the calculated score, candidates are classified into:

| Score Range | Verdict |
|-------------|----------|
| Above 75 | High |
| 50 – 75 | Medium |
| Below 50 | Low |

This helps recruiters prioritize candidate reviews.

---

### 📈 HR Dashboard

The HR dashboard provides:

- Candidate Name
- Evaluation Score
- Verdict Status
- Submission Records

This creates a centralized recruitment monitoring system.

---

## 🏗 System Architecture

```text
Resume Upload
      │
      ▼
Resume Parsing
(PDF / DOCX)
      │
      ▼
Text Extraction
      │
      ▼
Job Description Input
      │
      ▼
Sentence Transformer Model
      │
      ▼
Embedding Generation
      │
      ▼
Cosine Similarity
      │
      ▼
Relevance Score
      │
      ▼
Verdict Generation
      │
      ▼
Database Storage
      │
      ▼
HR Dashboard
```

---

## ⚙️ Technology Stack

### Frontend

- Streamlit

### Backend

- Python

### Natural Language Processing

- Sentence Transformers
- Hugging Face Transformers

### Machine Learning

- Scikit-Learn
- Cosine Similarity

### Document Processing

- PDFPlumber
- Docx2Txt

### Data Handling

- Pandas
- NumPy

### Database

- SQLite
- CSV Storage

---

## 🤖 AI Model Information

The project uses a fine-tuned Sentence Transformer model based on:

### Base Model

```text
sentence-transformers/all-MiniLM-L6-v2
```

### Model Features

- Transformer-Based Architecture
- 384-Dimensional Embeddings
- Semantic Text Understanding
- Cosine Similarity Matching
- Context-Aware Resume Analysis

The model converts both resumes and job descriptions into vector embeddings and compares them using semantic similarity techniques.

---

## 🔄 Workflow

### Step 1

Candidate uploads resume.

### Step 2

Resume content is extracted.

### Step 3

Job description is provided.

### Step 4

Both documents are converted into embeddings.

### Step 5

Cosine similarity score is calculated.

### Step 6

The system generates:

- Resume Score
- Candidate Verdict

### Step 7

Results are stored and displayed in the HR Dashboard.

---

## 📊 Output Example

### Candidate Result

```text
Candidate Name: Devakumar A

Resume Score: 87.45

Verdict: High
```

### HR Dashboard

```text
Name           Score      Verdict
---------------------------------
Devakumar      87.45      High
John           72.31      Medium
Alex           48.22      Low
```

---

## 💡 Real-World Applications

### Recruitment Automation

Automates initial resume screening.

### Applicant Tracking Systems (ATS)

Enhances candidate filtering and ranking.

### Human Resource Management

Improves recruitment efficiency.

### Talent Acquisition

Identifies suitable candidates faster.

### Corporate Hiring

Supports high-volume recruitment processes.

---

## 🌟 Key Benefits

- Reduces manual resume screening effort
- Improves recruitment speed
- Uses AI-powered semantic matching
- Provides objective candidate evaluation
- Enhances hiring accuracy
- Supports scalable recruitment workflows

---

## 🔮 Future Enhancements

- Skill Gap Analysis
- ATS Compatibility Scoring
- Resume Improvement Suggestions
- Interview Recommendation Engine
- Recruiter Analytics Dashboard
- Cloud Deployment
- Multi-Job Comparison
- Candidate Ranking System

---

## 📂 Repository Note

Due to the large size of trained AI models, dependencies, datasets, and generated resources, some files are not included in this repository.

The repository contains the complete application logic, source code, documentation, and implementation details required to understand and reproduce the project.

For project demonstration, collaboration, or access to additional project resources:

📧 **devak9391@gmail.com**

---

## 👨‍💻 Author

### Devakumar A

**B.Tech Computer Science and Engineering**  
Rajiv Gandhi College of Engineering and Technology (RGCET), Puducherry

### Achievements

- Scopus Published Researcher
- President – Mathoria Mathematics Club
- Scientific Program Trainee – Scientex MedTech Pvt Ltd
- NPTEL Elite + Gold Certification Holder
- AI, Machine Learning & Full Stack Development Enthusiast

### Connect

- GitHub: https://github.com/Devakumar-A
- ORCID: https://orcid.org/0009-0003-8934-6744

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

## 📜 License

This project is developed for educational, research, and recruitment automation purposes.
