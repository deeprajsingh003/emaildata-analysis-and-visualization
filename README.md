# 📧 Email Data Analysis & Visualization
---
## 📌 Project Overview

This project is based on the **Capstone: Retrieving, Processing, and Visualizing Data with Python** from the **Python for Everybody Specialization (University of Michigan)**.

The goal of the project is to download, clean, model, analyze, and visualize real-world email data from the Sakai open-source community

Developed as part of the **"Python for Everybody" Capstone** (University of Michigan), this toolset allows for:
1.  **Crawling** archived email data.
2.  **Cleaning & Modeling** the data into a Relational Database (SQLite).
3.  **Visualizing** key metrics like "Most Active Hours," "Top Contributors," and "Word Frequency Clouds."
---
## ⚙️ How It Works (The Pipeline)
The project runs in three sequential stages:
---
### 1. Data Extraction (`gmane.py`)
* Connects to a mailing list archive (e.g., Sakai Developer List).
* Scrapes raw email metadata and bodies.
* Stores raw data in `content.sqlite`.
---
### 2. Data Modeling (`gmodel.py`)
* Reads the raw crawl data.
* Cleanses the data (handling dates, sender normalization).
* Structures the data into a normalized Relational Schema (Tables: `Messages`, `Senders`, `Subjects`) in `index.sqlite`.
---
### 3. Analysis & Visualization
* **Basic Analysis (`gbasic.py`):** Computes statistics like Top 5 Senders and Organization distribution.
* **Timeline Visualization (`gline.py`):** Generates `gline.htm` to show email activity trends over time.
* **Word Cloud (`gword.py`):** Generates `gword.htm` to visualize the most frequent terms used in subjects.
---
## 📸 Project Results
*Verified outputs from my execution of the pipeline:*

### 🔹 Loading and Modeling Email Data Project Screenshots
*Screenshot 1*
![alt text](<Screenshot 1.png>)

*Screenshot 2*
![alt text](<Screenshot 2.png>)

*Screenshot 3*
![alt text](<Screenshot 3.png>)

*Screenshot 4*
![alt text](<Screenshot 4.png>)

### 🔹 Visualizing Email Data Projects Screenshots
*Screenshot 1*
![alt text](<Screenshot 1-1.png>)

*Screenshot 2*
![alt text](<Screenshot 2-1.png>)

*Screenshot 3*
![alt text](<Screenshot 3-1.png>)

*Screenshot 4*
![alt text](<Screenshot 4-1.png>)
---
## 🛠️ Tech Stack
* **Python:** Data Extraction & Processing
* **SQLite:** Relational Database Management
* **D3.js:** Interactive Data Visualization
* **JavaScript/HTML:** Frontend Reporting
---
## What I Learned
- Working with messy real-world data
- Designing relational databases
- Running ETL-style pipelines
- Visualizing trends to extract insights
- Importance of documentation and reproducibility
---
## ⚖️ Credits
* **Original Concept:** Dr. Charles Severance (University of Michigan).
* **Implementation & Analysis:** Deepraj Singh.
---
## Notes on Authorship & Learning
This is a **guided academic project**.  
I executed all steps independently by following course instructions and example videos,customized parameters, explored optional extensions, and documented results honestly.

The focus of this project was understanding **end-to-end data workflows** rather than claiming original algorithm design.
