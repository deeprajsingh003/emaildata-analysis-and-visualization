# 📧 Email Data Analysis & Visualization
---
## 📌 Project Overview

This project is based on the **Capstone: Retrieving, Processing,& Visualizing Data with Python** from the **Python for Everybody Specialization (University of Michigan)**.

The goal of the project is to download, clean, model, analyze, & visualize real-world email data from the Sakai open-source community

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
* Scrapes raw email metadata & bodies.
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
<img width="1365" height="714" alt="Screenshot 1" src="https://github.com/user-attachments/assets/a5dcd4b2-5565-4756-9cbb-6aec5677920b" />

*Screenshot 2*
<img width="1365" height="444" alt="Screenshot 2" src="https://github.com/user-attachments/assets/3a9d50a4-4c79-4859-a067-714b52619a0f" />

*Screenshot 3*
<img width="1365" height="719" alt="Screenshot 3" src="https://github.com/user-attachments/assets/5fe96e38-6837-4042-a528-0a2aaebfae02" />

*Screenshot 4*
<img width="1365" height="265" alt="Screenshot 4" src="https://github.com/user-attachments/assets/32e85df2-822a-4495-90bd-482a1caccf2b" />


### 🔹 Visualizing Email Data Projects Screenshots
*Screenshot 1*
<img width="1365" height="457" alt="Screenshot 1" src="https://github.com/user-attachments/assets/93a54414-3906-41bd-b1a1-3c1ece6eaacb" />

*Screenshot 2*
<img width="1278" height="678" alt="Screenshot 2" src="https://github.com/user-attachments/assets/f5a7babb-d8c2-49a2-8d19-f9840f4930e5" />

*Screenshot 3*
<img width="1287" height="626" alt="Screenshot 3" src="https://github.com/user-attachments/assets/51c5173b-17b3-453e-b791-0143ef7b588c" />

*Screenshot 4*
<img width="1293" height="614" alt="Screenshot 4" src="https://github.com/user-attachments/assets/8f653df9-764e-4eb8-af60-885ae8f53ee9" />

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

The focus of this project was understanding **end-to-end data workflows** rather than claiming original algorithm designs.
