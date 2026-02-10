# 📊 AI Job Market Analysis

## 📌 Project Overview
This project analyzes the AI job market to identify the most in-demand skills across different companies.  
Using Python and data visualization techniques, the project uncovers hiring trends, skill distributions, and company-wise demand for AI-related skills.

This project is suitable for **data science beginners/freshers** and demonstrates skills in **data cleaning, transformation, and visualization**.

---

## 📂 Dataset
The dataset contains AI job postings with information such as:
- Company Name
- Job Role / Job Description
- Required Skills

Skills were extracted and transformed into a structured format for analysis.

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- WordCloud  
- Jupyter Notebook  

---

## 🔄 Data Processing Workflow
1. Loaded raw AI job market data  
2. Cleaned and preprocessed the dataset  
3. Extracted skills from job descriptions  
4. Normalized data using `stack()` and `crosstab()`  
5. Created a final dataset with:
   - Company Name  
   - Skills Required  

---

## 📊 Visual Insights

### 🔹 Job Role Distribution
![Job Role Distribution](images/Job Role Distribution.png)

### 🔹 Skills Count per Company
![Skills Count per Company](images/Skills Count per Company.png)

### 🔹 Top 10 Companies by Skill Demand
![Top 10 Companies by Skill Demand](images/Top 10 Companies by Skill Demand.png)

### 🔹 Top 10 Most In-Demand Skills
![Top 10 Most In-Demand Skills](images/Top 10 Most In-Demand Skills.png)

### 🔹 Top 10 Skills
[![Top 10 Skills](images/Top 10 Skills.png)](images/Top 10 Skills.png)

### 🔹 Top 15 Skills Distribution
![Top 15 Skills Distribution](images/Top 15 Skills Distribution.png)

### 🔹 Top 5 Skills Share
![Top 5 Skills Share](images/Top 5 Skills Share.png)

### 🔹 Top Companies vs Top Skills Heatmap
![Top Companies vs Top Skills Heatmap](images/Top Companies vs Top Skills Heatmap.png)

---

## 🔍 Key Insights
- Certain skills consistently appear across multiple companies  
- Some companies demand a wider range of skills compared to others  
- Skill requirements vary significantly across organizations  
- A small set of skills dominates the AI job market demand  

---

## 🚀 How to Run the Project

### 1️⃣ Install required libraries
```bash
pip install -r requirements.txt
