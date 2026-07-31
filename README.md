# 🎯 ResumeIQ — Intelligent Resume & Job Match Analyzer

ResumeIQ is a full-stack Natural Language Processing (NLP) application built in Python that automates candidate resume screening, skill extraction, and job description (JD) matching. 

### 🌟 Project Highlights & Features
- 📄 **PDF Text Extraction**: Uses `pdfplumber` to extract clean text from multi-page PDF resumes.
- 🧹 **Text Preprocessing**: Implements `NLTK` tokenization, stop-word removal, and text normalization.
- 🎯 **Dual-Engine Job Matching**: Combines set-based Skill Overlap scoring with `scikit-learn` TF-IDF Cosine Similarity for deep contextual alignment.
- 📊 **Resume Quality Scoring**: Evaluates structural completeness across 9 key sections (Projects, Contact, Experience, GitHub, Education, etc.) on a 100-point scale.
- 💼 **Role Recommender**: Recommends top matching job roles based on candidate skill vectors.
- 📈 **Visual HTML Reports**: Automatically generates standalone, responsive HTML dashboards with visual meters, skill badges, and improvement tips.
- 🧪 **Unit Tested**: Backed by 65+ automated unit and integration tests.

### 🛠️ Tech Stack & Integrations
- **Languages**: Python (100% Core Engine), HTML5 & CSS3 (Report Generation), JSON (Taxonomy Data)
- **ML & NLP**: Scikit-Learn (TF-IDF & Cosine Similarity), NLTK, NumPy, Pandas
- **Document Processing**: PDFPlumber, PDFMiner.six
