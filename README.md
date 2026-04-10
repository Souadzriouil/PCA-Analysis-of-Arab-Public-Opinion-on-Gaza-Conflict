# 📊 PCA Analysis of Arab Public Opinion on Gaza Conflict

## 📌 Overview
This project explores **Arab public opinion on the Gaza conflict** using **Principal Component Analysis (PCA)**.

The goal is to identify the **key factors influencing opinions across different Arab countries** and reduce data dimensionality while preserving the most important information.

---

## 🎯 Objectives
- Perform Exploratory Data Analysis (EDA)
- Analyze relationships between variables
- Apply PCA for dimensionality reduction
- Identify the most influential factors
- Provide clear data-driven insights

---

## 📂 Dataset
- Source: Arab Center for Research & Policy Studies  
- Sample size: ~8000 respondents  
- Countries: 16 Arab countries  

### Variables:
- **SMPEU** → Support of US military/political actions  
- **MDAGAEI** → Lack of Arab government action  
- **AN** → Normalization agreements  
- **SGOI** → Western government support  
- **MDADONUI** → UN inaction  
- **MDPPLAPI** → Palestinian authority position  
- **Autre / NS** → Other responses  

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- R (FactoMineR)
- Excel (XLSTAT)
- Statistics & PCA

---

## ⚙️ Project Structure

PCA-Analysis-of-Arab-Public-Opinion-on-Gaza-Conflict/
│
├── data/              # Dataset  
├── notebooks/         # Jupyter Notebook (EDA & PCA)  
├── report/            # Final PDF report  
├── visuals/           # Plots and figures  
├── requirements.txt   # Dependencies  
└── README.md  

---

## 📊 Visualizations

### 🔹 Distribution of SMPEU
![Histogram](visuals/histogram_smpeu.png)

### 🔹 Correlation Heatmap
visuals/Heatmap.png

### 🔹 Scree Plot (PCA)
![Scree Plot](visuals/scree_plot.png)

### 🔹 Observations by Country
![Qualitative](visuals/qualitative_analysis.png)

---

## 📈 Key Results
- The first **2 principal components explain ~87.9% of total variance**
- Strong correlation between **AN** and **MDADONUI**
- SMPEU variable follows a near-normal distribution
- Balanced observations across countries

---

## 🧠 Insights
- Political and international factors strongly influence public opinion  
- PCA effectively reduced complexity while preserving key information  
- Two dimensions are sufficient to represent the dataset  

---

## ▶️ How to Run

Install dependencies:

pip install -r requirements.txt

Run the notebook:

jupyter notebook notebooks/ACP_project.ipynb

---

## 👩‍💻 Author
**Souad Zriouil**  
AI Engineer | Data Scientist | Machine Learning | NLP | LLM  

🔗 LinkedIn: https://www.linkedin.com/

---

## ⭐ Project Value
This project demonstrates:
- Strong skills in **data analysis & statistics**
- Practical use of **PCA on real-world data**
- Ability to work with **Python, R, and Excel**
- Clear data visualization and interpretation
