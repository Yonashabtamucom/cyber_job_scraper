#  Cyber Job Scraper

A complete **data science + cybersecurity project** that scrapes, cleans, and analyzes cybersecurity job listings to uncover market trends, top companies, and in-demand skills.

---

##  Project Goal

To analyze the **cybersecurity job market** by:
- Collecting real job data from online sources  
- Filtering only cybersecurity-related roles  
- Extracting insights like top skills and hiring companies  

---

##  Features

- 🔍 Web scraping using Python  
- 🧹 Data cleaning & filtering (cybersecurity-focused)  
- 📊 Data analysis with pandas  
- 📈 Visualization with matplotlib & seaborn  
- 📓 Interactive exploration using Jupyter Notebook  
- 📄 Automated report generation (charts + PDF)

---

##  Project Structure

cyber_job_scraper/
│
├── data/
│ ├── raw/ # Raw scraped data
│ └── processed/ # Cleaned cybersecurity jobs
│
├── scripts/
│ ├── scraper.py # Collect job data
│ ├── clean_data.py # Filter cybersecurity jobs
│ └── analysis.py # Analyze & generate reports
│
├── notebooks/
│ └── exploration.ipynb # Data exploration notebook
│
├── reports/
│ ├── figures/ # Saved charts
│ └── pdf/ # Final PDF report
│
└── README.md

---

##  Installation

### 1. Clone the repository
```bash
git clone https://github.com/Yonashabtamucom/cyber_job_scraper.git
cd cyber_job_scraper

## Usage

1. Scrape job data
python scripts/scraper.py

2. Clean & filter cybersecurity jobs
python scripts/clean_data.py

3.Analyze data & generate charts
python scripts/analysis.py

4.Explore with notebook
jupyter notebook notebooks/exploration.ipynb

## Filtering Logic

Jobs are filtered using cybersecurity keywords:
security | cyber | soc | infosec | devsecops | penetration | threat | vulnerability

## Additional filtering removes irrelevant roles like:

   marketing
   sales
   payroll
   social media

## Outputs

  📁 data/processed/cybersecurity_jobs.csv → Clean dataset
  📊 reports/figures/ → Charts (top companies, skills, titles)
  📄 reports/pdf/cyber_jobs_report.pdf → Final report

## What I Learned

Web scraping with APIs
Data cleaning & filtering techniques
Handling noisy real-world data
Data visualization and reporting
Building a complete data pipeline

## Future Improvements

🌐 Add more job sources (LinkedIn, Indeed)
📊 Build dashboard (Streamlit)
🤖 Use ML for job classification
⏱ Automate daily data updates

## License

MIT License

⭐ If you like this project, give it a star!


---

🔥 This version is:
- Clean   
- Professional 
- Portfolio-ready   
- GitHub-friendly  

---

If you want next level 😏  
👉 I can help you **turn this into a full portfolio project with a dashboard (Streamlit)** — that’s what recruiters LOVE.

Just say: **“dashboard”** 
