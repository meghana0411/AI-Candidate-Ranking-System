## Key Highlights

- Built an AI-powered candidate ranking system
- Uses semantic search with Sentence Transformers
- Supports OCR for scanned resumes
- Performs skill extraction and matching
- Implements hybrid scoring for ranking candidates
- Evaluated using multiple ranking and relevance tests

# AI Candidate Ranking System

An AI-powered recruitment system that ranks candidates based on resume content, semantic similarity, and skill matching. The system helps recruiters identify the most relevant candidates for a job description using NLP, embeddings, OCR, and hybrid scoring techniques.

## Features

* Resume PDF Processing
* OCR Support for Scanned Resumes
* Semantic Search using Sentence Transformers
* Skill Extraction and Matching
* Hybrid Candidate Scoring
* Candidate Ranking and Recommendations
* Resume Analysis and Evidence Generation

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-Learn
* Sentence Transformers
* PDFPlumber
* Tesseract OCR
* Matplotlib

## Project Workflow

Job Description
→ Skill Extraction
→ Resume Processing
→ OCR / Text Extraction
→ Embedding Generation
→ Semantic Similarity Calculation
→ Skill Matching
→ Hybrid Scoring
→ Candidate Ranking

## Scoring Method

Final Score = Semantic Match + Skill Match

The system combines:

* Semantic similarity between job descriptions and resumes
* Skill overlap analysis
* Evidence-based ranking

## Testing Performed

* Relevant vs Non-Relevant Resume Ranking
* Cross-Domain Resume Testing
* Perfect Candidate Benchmark Testing
* Runtime Evaluation
* Score Distribution Analysis
* Recommendation Bucket Validation

## Sample Output

The system generates:

* Candidate Rankings
* Semantic Match Scores
* Skill Match Scores
* Final Scores
* Recommendation Categories (Strong Fit, Good Fit, Potential Fit, Weak Fit)
* Matched and Missing Skills

## Future Improvements

* Full-Stack Web Application
* Recruiter Dashboard
* Real-Time Resume Processing
* Vector Database Integration (pgvector)
* Advanced Analytics and Reporting

## Author

Saimeghana Vadluri
