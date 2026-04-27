# 🧠 AI Research Trends Visualization (2019–2025)

This project presents a data-driven visualization of the evolution of AI research between 2019 and 2025 across four major domains:

- Classical Machine Learning  
- Deep Learning  
- Generative AI  
- AI Agents  

The objective is to highlight **structural trends in AI research**, rather than provide exact publication counts.

---

## 📊 Overview

The visualization shows the evolution of research activity across AI subfields using a grouped bar chart.

It illustrates a key idea:

> AI is not replacing itself — it is evolving as a layered system.

---

## 🧠 Key Insights

- **Machine Learning** is stabilizing as a mature and foundational layer  
- **Deep Learning** remains the dominant backbone of modern AI  
- **Generative AI** shows rapid acceleration driven by foundation models  
- **AI Agents** are emerging as a new research frontier focused on autonomy  

---

## 📌 Data Sources & Methodology

The dataset is a **trend-based reconstruction** derived from:

- **arXiv API** (category: *cs.AI*)  
- **Stanford AI Index Report**  

### 🔎 Filtering Approach

Publications were filtered using **thematic keywords** extracted from paper abstracts to classify them into four domains:

- Machine Learning  
- Deep Learning  
- Generative AI  
- AI Agents  

This approach aims to capture **research signals and trends**, rather than provide an exhaustive or official count of publications.

⚠️ Important:
- arXiv categorization may overlap between fields  
- Some research areas (e.g., AI Agents) may be embedded within broader categories (e.g., LLMs / Generative AI)  
- Recent years may have incomplete indexing  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- Matplotlib  
- NumPy  

---

## 📈 Visualization Details

- Grouped bar chart (2019–2025)  
- Color-coded AI domains  
- Value annotations on each bar  
- Grid for readability  
- High-resolution export (PNG)

---

## ▶️ How to Run

Install dependencies:

```bash
pip install pandas matplotlib numpy
