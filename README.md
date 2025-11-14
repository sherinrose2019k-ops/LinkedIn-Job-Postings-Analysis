# LinkedIn-Job-Postings-Analysis
This project analyzes real LinkedIn job postings (2023–2024) to uncover insights about the modern job market.
Even though the dataset covers 2023–24, the insights remain highly relevant for understanding **today’s job market**, especially in data and tech-related fields
## 🔍 Objectives
- Identify most in-demand job titles
- Analyze trending skills
- Explore hiring patterns across companies and locations
- Extract key skills from job descriptions using NLP
- Visualize the job market with charts and word clouds
## Dataset Source:
Kaggle — LinkedIn Job Postings (2023–2024)  https://www.kaggle.com/datasets/arshkon/linkedin-job-postings
Rows: ~124,000  
Main fields: job_title, company_name, job_location, job_description, salary, post_date
Data Cleaning
- Removed duplicates
- Standardized job titles and locations
- Filled missing values
- Cleaned text fields
## 📊 Analysis Performed
### Job Market Trends
- Top job titles
- Top companies hiring
- Most common locations
### Skill Extraction (NLP)
Using **SpaCy + NLTK**, I extracted skills mentioned inside job descriptions.
**Skills extracted include:**
- Python  
- SQL  
- Excel  
- Tableau  
- Power BI  
- AWS / Azure  
- Machine Learning  
- Communication  
- Project Management  
I created a frequency distribution and visualized the **Top 20 Most In-Demand Skills**.
## 📈 Visualizations
- Bar charts for job titles, companies, skills
- Word cloud for job descriptions
- Skill frequency plots
## 🛠️ Tools Used
- Python
- Pandas, NumPy
- Matplotlib
- Seaborn
- NLTK & SpaCy (NLP)
- WordCloud
## 📌 Results
- Python, SQL, Excel, Tableau are the most required skills
- Data-related roles dominate LinkedIn postings
- Remote job opportunities are increasing
- Companies emphasize soft skills like communication & teamwork

🔮 Future Improvements
- Build an interactive **dashboard** (Tableau or Power BI).  
- Add clustering to group similar job descriptions.  
- Use BERT or other deep learning models for advanced text analysis.  
- Include time-series trend analysis.
  
 📊 Key Insights
- **Python, SQL, and Excel** are the most demanded skills across industries.  
- Data-related roles such as **Data Analyst** and **BI Analyst** dominate LinkedIn postings.  
- Soft skills like **communication** and **problem-solving** appear frequently.  
- Remote job opportunities have increased significantly.  
- Tech companies and consulting firms are among the top employers.
## 👤 Author
Sherin 

LinkedIn: www.linkedin.com/in/sherin-rose-anto-064543201
