# **Nirmaan AI – Communication Scorer**

A Streamlit-based evaluation tool built for the **Nirmaan AI Intern Case Study**.
The system scores student self-introductions using a **rubric-driven model** combined with **NLP techniques**, including grammar analysis, sentiment scoring, filler-word detection, vocabulary richness, and optional semantic similarity.

---

## **Features**

* Rubric-based scoring aligned with the official case-study criteria
* Content & Structure, Speech Rate, Grammar, Vocabulary, Clarity, Engagement
* Modern dark-themed Streamlit UI
* Supports text input, file upload, and sample text
* Generates detailed JSON output for automation or reporting
* Fully project-relative paths (GitHub & deployment friendly)

---

## **Run Locally**

```bash
pip install -r requirements.txt
streamlit run app.py
```

App opens at: **(https://nirmaan-ai.streamlit.app/)**

---

## **Project Structure**

```
app.py                  # Streamlit UI
rubric_loader.py        # Loads rubric from XLSX/CSV
scoring_logic.py        # Complete scoring engine
Case study for interns.xlsx
Sample text for case study.txt
requirements.txt
```

---

## **Usage**

1. Paste or upload a transcript
2. Click **Score**
3. View per-criterion scores, weighted contributions, and JSON output
4. Download the final scoring JSON

---

