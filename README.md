


# No Fluff Jobs Scraper & Dataset Extractor 🚀

A lightweight, powerful web scraper designed to extract tech job market data from **No Fluff Jobs**. Perfect for data analysts, job market researchers, and developers looking for real-world datasets containing salary ranges, tech stacks, seniority levels, and remote job offers.

---

## 🌟 Key Features

* **Complete Offer Details:** Extracts job titles, companies, locations, requirements, and categories.
* **Salary Insights:** Captures precise salary ranges (B2B & Employment Contracts) in original currencies.
* **Tech Stack Breakdown:** Extracts required technologies, frameworks, and skill levels (Python, SQL, React, AWS, etc.).
* **Flexible Export:** Download fresh datasets in **CSV, JSON, Excel, or XML** formats.
* **No Setup Required:** Runs smoothly in the cloud via Apify without local environment issues.

---

## 📊 Extracted Data Structure

The scraper returns structured output ready for Pandas, PowerBI, or Excel analysis:

```json
[
  {
    "title": "Senior Python Developer",
    "company": "TechSolutions",
    "salary_from": 18000,
    "salary_to": 24000,
    "currency": "PLN",
    "employment_type": "B2B",
    "seniority": "Senior",
    "technology": "Python",
    "must_have_skills": ["Python", "Django", "PostgreSQL", "Docker"],
    "location": "Warsaw (Remote)",
    "url": "https://nofluffjobs.com/job/sample-id"


  }
]

