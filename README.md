# AI and the Future of Entry-Level Jobs: Are Recent Graduates at Risk?


## Motivation
We are entering the workforce during a period of rapid growth in artificial intelligence and automation. Unlike previous generations, who often had clearer and more stable career paths, recent graduates face increasing uncertainty in the job market. In this era of digital transformation, there is a growing concern that automation may reduce the availability of entry-level positions. This project aims to analyze whether this concern is supported by data, and to examine the extent to which AI is affecting employment opportunities for recent graduates. 

---

## Hypotheses
This project investigates how artificial intelligence is reshaping entry-level job opportunities through three key dimensions: job accessibility, economic impact, and educational requirements.

---

### Hypothesis 1: Demand vs Entry-Level Access
**Question:** Do high-demand AI jobs offer fewer entry-level opportunities?

- **H0:** Demand score is not related to experience level  
- **H1:** High-demand jobs are less likely to be entry-level  

---

### Hypothesis 2: Salary Inequality
**Question:** Does AI increase salary differences between entry-level and senior roles?

- **H0:** AI salary premium is similar across experience levels  
- **H1:** Senior roles benefit more from AI salary premiums  

---

### Hypothesis 3: Education Requirements
**Question:** Do entry-level AI jobs still require formal degrees?

- **H0:** Education requirements are independent of experience level  
- **H1:** Entry-level jobs still require formal degrees  

---

### Columns Used

| Hypothesis                                      | Columns                                                                 |
|------------------------------------------------|-------------------------------------------------------------------------|
| H1: Demand vs Entry-Level Accessibility         | demand_score, experience_level                                          |
| H2: Salary Premium Inequality                  | ai_salary_premium_pct, experience_level, annual_salary_usd              |
| H3: Education Requirements                     | education_required, experience_level, required_skills                   |

---

## Datasets

This project uses two complementary datasets to analyze how artificial intelligence is affecting entry-level job opportunities.

---

### Dataset 1: AI Jobs Market (2025–2026)

This dataset focuses on the **AI job market**, including salary trends, demand, and job requirements.

**Key features used:**
- demand_score → measures how in-demand a role is  
- experience_level → identifies entry-level vs senior roles  
- annual_salary_usd → salary analysis  
- ai_salary_premium_pct → additional salary advantage in AI roles  
- education_required → degree requirements  
- required_skills → skills expected from candidates  

**Purpose:**  
Used to analyze how AI demand and salary dynamics vary across experience levels.

---

### Dataset 2: AI Job Listings

This dataset provides detailed information about **job postings and hiring requirements**.

**Key features used:**
- experience_level → entry-level vs experienced roles  
- education_required → degree vs non-degree jobs  
- years_experience → hiring expectations  
- required_skills → skill requirements  
- salary_usd → salary comparison  
- industry → sector-based analysis  

**Purpose:**  
Used to evaluate job accessibility, hiring expectations, and skill requirements for recent graduates.

---

### Why Two Datasets?

Each dataset captures a different perspective:

- Dataset 1 → **market trends** (demand, salary, AI premium)  
- Dataset 2 → **job-level details** (requirements, experience, skills)  

By combining them, the project can:
- compare **high-demand vs entry-level accessibility**  
- analyze **salary differences across experience levels**  
- examine whether **education is still required in AI jobs**  

This provides a more complete and reliable understanding of how AI is shaping early career opportunities.


