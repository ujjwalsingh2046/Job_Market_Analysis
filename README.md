# Job Market Analysis in the Data Domain 📊

## 1. Project Overview

### 1.1 Goal
The primary objective of this project is to conduct an **Exploratory Data Analysis (EDA)** on job listings in the data domain. It aims to extract **actionable insights** that can help professionals plan their careers and understand the **current job market**. These insights focus on in-demand roles, required skills, salary patterns, remote opportunities, and location-based demand across **global and Indian markets**.

### 1.2 Scope
This project focuses on roles like **Data Analyst, Data Scientist, and Data Engineer**, extracting skill, salary, location, and experience trends from job postings. It also highlights **India-specific insights**. The data is analyzed to provide a clear understanding of job dynamics using Python.

### 1.3 Tech Stack
- **Python**
  - `Pandas` for data analysis
  - `Matplotlib` and `Seaborn` for visualizations
  - Jupyter Notebooks for execution and narration

---

## 2. Key Insights, Findings and Visualizations

---

### 🔹 Skill Demand Analysis

The graph reveals **clear specialization trends** across data roles:

- **Data Analysts** heavily rely on **SQL (47.1%)** and **Excel (34.1%)**, showing that traditional tools are still dominant. Python (29.2%) is gaining ground, indicating a shift toward scripting-based analysis. Visualization tools like **Tableau** and **Power BI** are moderately demanded, suggesting that storytelling with data remains important but secondary.

- **Data Scientists** show a strong preference for **Python (66%)**, followed by **SQL (45.8%)**, making coding and querying essential. The presence of **R (34.6%)** and **SAS (17.1%)** suggests statistical modeling is still relevant in certain segments. Visualization (Tableau) is far less emphasized in this role.

- **Data Engineers** show a blend of **traditional querying (SQL – 60.7%)** and **scripting (Python – 58%)**, but what’s most unique is the strong presence of **cloud tech**: **AWS (33.3%)**, **Azure (32.6%)**, and **Spark (28.8%)**. This reflects how engineering roles are evolving toward managing large-scale, distributed systems.

### 🧠 Key Takeaways:
- **SQL + Python** are core skills across all roles.
- **Excel** is still very relevant — especially for Analysts.
- **Cloud tools** are now essential for Engineering roles.
- **Visualization skills** are secondary but useful for communication-heavy roles like Data Analyst.
 
  <img width="700" height="480" alt="image" src="https://github.com/user-attachments/assets/c1b4b272-86c2-4030-8800-42142e7dd466" />

---

### 🔹 Global Job Role Demand – Top 10 Roles

- **Data Analyst** leads the global job market with over **196,000 listings**, followed closely by **Data Engineer** (186k+) and **Data Scientist** (172k+), confirming their dominance in the data ecosystem.
- Non-core data roles such as **Business Analyst** and **Software Engineer** also make it to the top 10, reflecting the crossover of analytical and technical skills across job categories.
- **Senior roles** like *Senior Data Engineer* and *Senior Data Scientist* have substantial visibility, suggesting that companies are equally investing in experienced professionals.
- **Machine Learning Engineers** and **Cloud Engineers**, although critical in advanced analytics and infrastructure, are relatively lower in volume—possibly due to their niche, specialized requirements.
  
<img width="850" height="550" alt="image" src="https://github.com/user-attachments/assets/2c8c9912-a224-45dd-ae63-163d105d506d" />

---

### 🔹 India-Specific Job Role Demand – Top 10 Roles

- In stark contrast to global trends, **Data Engineer** roles dominate in India with **19,000+ postings**, significantly ahead of **Data Scientists** (13k+) and **Data Analysts** (6k+).
- This implies India’s growing demand for infrastructure-heavy roles, likely driven by the expansion of cloud adoption and big data systems.
- Senior positions like *Senior Data Engineer* and *Senior Data Scientist* show healthy demand, indicating that Indian employers are scaling mature data teams.
- Advanced and niche roles like **ML Engineers** and **Cloud Engineers** are fewer, reinforcing that the Indian job market is still catching up in cutting-edge tech roles.
  
<img width="850" height="550" alt="image" src="https://github.com/user-attachments/assets/72e9e1da-f7e4-4a6b-aeb5-650f6e05cf39" />

---

### 🔹 Skill Demand vs. Salary for Data Analysts

#### 📈 Top In-Demand Skills
- The most **frequently required** skills for Data Analysts are practical tools like **Excel**, **Word**, **PowerPoint**, and **Power BI**, reflecting the need for day-to-day reporting, presentations, and dashboard creation.
- **SQL**, **Python**, and **Tableau** continue to dominate the technical skill requirements, highlighting their critical role in data handling and visualization.
- While these tools are commonly requested, their **median salaries remain moderate**, around the $90K mark, showing that high demand doesn’t always equate to high pay.

#### 💰 Top Paying Skills
- On the other end, niche technologies such as **Solidity**, **SVN**, **GitLab**, and **Terraform** top the salary chart, offering **$150K–$190K+ median salaries**.
- Skills like **Datarobot**, **MxNet**, and **Golang**, though **less frequently listed**, are extremely valuable in specialized roles like ML automation, cloud engineering, or blockchain applications.
- These insights suggest that **rare but high-impact skills** can significantly boost earning potential, even if they are not required in most traditional data analyst roles.

<img width="850" height="990" alt="image" src="https://github.com/user-attachments/assets/4dd2b50f-203c-4240-8b2b-4327ad3cd978" />

---

### 🔹 Remote Work
- A good percentage of roles explicitly allow **work-from-home** (remote jobs).
- Surprisingly, remote roles are more common in Indian listings than in Global listings with **8.9% at the global level but 11.2% at Indian level**
  <img width="455" height="270" alt="image" src="https://github.com/user-attachments/assets/fbf9483d-11b9-410c-b7b5-fbe1d705a99a" /> <img width="450" height="270" alt="image" src="https://github.com/user-attachments/assets/4a4b9a56-2d68-4ef3-a6ff-ab9787c11b35" />

---
  
### 📊 Skill Trends Throughout 2023

#### 🔹 Data Analyst
- **SQL** remained the most consistently in-demand skill, peaking in January and August before seeing a gradual decline towards December.
- A surprising surge in **Excel** demand started around July, briefly surpassing Python and Tableau in August—indicating a potential return to basics in many analyst roles.
- **Python**, **Tableau**, and **Power BI** saw moderate but steady interest, with minor bumps mid-year.
- Insight: There was **renewed demand for simpler tools (Excel)** in late 2023, suggesting companies prioritized quick reporting and spreadsheet-based workflows.

#### 🔹 Data Scientist
- **Python** held the lead across all months, with spikes in January and August—possibly due to hiring cycles or project kickoffs.
- **SQL** followed a similar but slightly subdued curve, reflecting its supportive role in Data Science.
- **R**, **SAS**, and **Tableau** maintained low but consistent demand, showing they are still relevant in certain domains (e.g., research, legacy systems).
- Insight: **Python’s dominance** remained unshaken, and **August saw a hiring spike**, making it a critical window for job seekers.

#### 🔹 Data Engineer
- **SQL** and **Python** led consistently throughout the year, with both peaking in January and August.
- **AWS** and **Azure** followed a parallel trend, highlighting sustained demand for **cloud infrastructure** expertise.
- **Spark** maintained a steady presence, confirming its role in big data and ETL pipelines.
- Insight: The data engineer market in 2023 was **heavily cloud-driven**, with **SQL and Python forming the backbone** of most roles.

<img width="750" height="900" alt="image" src="https://github.com/user-attachments/assets/d86a1353-a49a-43ff-b044-5721b659c758" />

---

### 🔸 Top Hiring Companies in India
A bar chart showcasing the **top 20 companies hiring** for data roles in India.
<img width="900" height="1150" alt="image" src="https://github.com/user-attachments/assets/39f13fb6-3a4f-4489-aa13-6b064edbb6cd" />

---

### 🧠 Optimal Skills for Data Analysts (Globally)

This scatter plot highlights the most **strategic skills**—those that strike the best balance between **demand (job presence)** and **earning potential (median salary)**.

#### 🔹 Key Takeaways:
- **SQL** dominates in job presence (56%) and still offers a solid median salary (~$92K), making it a **non-negotiable core skill**.
- **Python** stands out as the **best-paid skill** (~$98K) while also being highly demanded—offering the **best overall balance**.
- **Excel** is in high demand but is associated with lower salaries (~$84K), indicating it’s a baseline skill.
- **Tableau** and **R** are moderate in demand but offer **above-average salaries**, making them great **specialization add-ons**.
- **PowerPoint** and **Word** are low in both salary and demand, suggesting they’re **supportive but non-strategic** skills.

#### 🎯 Insight:
For aspiring analysts aiming for **both high opportunity and high pay**, mastering a combo of **SQL + Python + Tableau** seems most optimal.

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/9a4681b6-4ffb-40c8-841c-985bf6e9bb54" />


These plots were created using `matplotlib.pyplot` and `seaborn`.

---

## 3. How to Run This Project 💻

### 3.1 Prerequisites
To run this project, install the following Python libraries:

install the following libraries: numpy, pandas, matplotlib, seaborn, ast

## 3.2 Execution

1. Open Jupyter Notebook.
2. Launch the following notebooks one by one:
   - 1_EDA.ipynb
   - 2_Skill_Demand.ipynb
   - 3_Skill_Trend.ipynb
   - 4_Salary_Analysis.ipynb
  
3. Run all the cells sequentially (Shift + Enter).

---

## 4. Future Work 🚀

### 🧠 Salary Prediction Model
In the next phase of this project, a **machine learning model** will be developed to predict salaries based on:
- Job location  
- Required skillset  
- Candidate's years of experience  

This will involve collecting more data and learning appropriate modeling techniques to implement a robust salary prediction system.

---

## 5. About the Project 🧭

This repository is designed to empower job seekers in the **data field** with the right market intelligence to make better career decisions. From job demand and skill trends to salary ranges and remote opportunities—this project delivers **meaningful, visual insights** through data.

---

## 6. 📌 Acknowledgements
This project uses job data sourced from HuggingFace. It is inspired by real-world career planning challenges faced by data enthusiasts and professionals making a career switch.

---
