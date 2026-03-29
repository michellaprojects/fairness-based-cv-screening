### 1. Getting Started
- Clone the repo and clone your fork: 

git clone https://github.com/<your-username>/fairness-based-cv-screening.git
cd fairness-based-cv-screening

- Make branch (per feature/change): 

git checkout -b feature/<short-description>

### 2. Setup 
- Install Requirements

pip install -r requirements.txt

### 3. Structure

/data        # datasets (CVs, job descriptions)
/src         # preprocessing, NLP models, scoring logic
/models      # saved/trained models
/tests       # unit tests
/notebooks   # experiments and analysis

### 4. Standard (pls follow)
Python 3.10+
Follow PEP8
Keep functions modular (preprocessing, feature extraction, scoring separated)
Avoid hardcoding paths or dataset assumptions

### 5. Commit Guidelines
Use structure like: 
feat: add bias mitigation method
fix: correct similarity calculation
docs: update contributing guide

### 6. Things to check before creating pull request
 Feature/bug clearly explained
 Reproducible results (same result for all user)
 No sensitive data included (kalo ada API jangan di push)