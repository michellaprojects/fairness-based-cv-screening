# Contributing Guide

## 1. Getting Started

Clone the repository and your fork:

```bash
git clone https://github.com/<your-username>/fairness-based-cv-screening.git
cd fairness-based-cv-screening
```

Create a new branch for your feature or fix:

```bash
git checkout -b feature/<your-feature-name>
```

---

## 2. Setup

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 3. Project Structure

```
/data        # Datasets (CVs, job descriptions)
/src         # Preprocessing, NLP models, scoring logic
/models      # Saved / trained models
/tests       # Unit tests
/notebooks   # Experiments and analysis
```

---

## 4. Coding Standards

* Use Python 3.10+
* Follow PEP 8
* Keep functions modular:

  * preprocessing
  * feature extraction
  * scoring
* Avoid hardcoding paths or dataset assumptions

---

## 5. Commit Guidelines

Use conventional commit messages:

```
feat: add bias mitigation method
fix: correct similarity calculation
docs: update contributing guide
```

---

## 6. Before Submitting a Pull Request

Ensure that:

* The feature or bug fix is clearly explained
* Results are reproducible (consistent across runs)
* No sensitive data is included (e.g., API keys, private datasets)
