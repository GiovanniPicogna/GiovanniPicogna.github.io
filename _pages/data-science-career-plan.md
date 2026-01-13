---
layout: archive
title: "Career"
permalink: /blog/
author_profile: true
---

# Data Science Career Transition Plan
## From Astrophysics Post-Doc to Munich Industry (2026–2028)

**Background:** PhD in Astrophysics, 10+ years post-doc experience with hydrodynamical simulations, numerical modeling, and large-scale data analysis.

**Target:** Data Scientist position at a Munich-based company (automotive, tech, insurance, or deep-tech startup).

**Timeline:** 24 months alongside current position.

---

## Phase 1: Foundations (Months 1–6)
*January 2026 – June 2026*

### SQL Mastery (Priority: 🔴 Critical)
Your biggest gap as a physicist—industry uses relational databases, not HDF5/FITS files.

| Resource | Type | Cost | Duration |
|----------|------|------|----------|
| [Mode Analytics SQL Tutorial](https://mode.com/sql-tutorial/) | Free course | €0 | 2 weeks |
| [DataCamp SQL Fundamentals](https://www.datacamp.com/tracks/sql-fundamentals) | Track | €25/month | 4 weeks |
| [LeetCode SQL Problems](https://leetcode.com/problemset/database/) | Practice | Free | Ongoing |

**Milestone:** Complete 50+ SQL problems, build a project querying real datasets.

### Software Engineering Practices (Priority: 🔴 Critical)
Move beyond Jupyter notebooks to production-quality code.

- [ ] Git workflow: branching, pull requests, code review
- [ ] Python project structure: `pyproject.toml`, virtual environments
- [ ] Testing: pytest basics, CI/CD with GitHub Actions
- [ ] Documentation: docstrings, README standards

**Resource:** [Real Python - Python Project Best Practices](https://realpython.com/)

### ML Refresher (Priority: 🟡 Medium)
Formalize knowledge you likely already have intuitively.

- [ ] Scikit-learn official tutorials (2 weeks)
- [ ] Hands-On ML with Scikit-Learn (Aurélien Géron) — Chapters 1-8
- [ ] Complete 2 Kaggle "Getting Started" competitions

---

## Phase 2: Deep Learning & Certification (Months 7–12)
*July 2026 – December 2026*

### Deep Learning Specialization (Priority: 🔴 Critical)
**Provider:** DeepLearning.AI via Coursera  
**Cost:** ~€42/month (Coursera Plus)  
**Duration:** 3 months @ 10 hrs/week

Courses:

1. Neural Networks and Deep Learning
2. Improving Deep Neural Networks
3. Structuring ML Projects
4. Convolutional Neural Networks
5. Sequence Models

**Why:** Industry-standard credential, taught by Andrew Ng, highly recognized in German market.

### Azure Data Scientist Associate (DP-100)
**Exam Cost:** ~€165  
**Prep Time:** 6-8 weeks

Study resources:

- [ ] Microsoft Learn: DP-100 learning path (free)
- [ ] [Azure ML documentation](https://learn.microsoft.com/en-us/azure/machine-learning/)
- [ ] Practice exams on MeasureUp

**Why:** Azure dominates German enterprise (BMW, Siemens, Allianz all use it heavily). This is the highest-value certification for Munich market.

---

## Phase 3: MLOps & Cloud (Months 13–18)
*January 2027 – June 2027*

### MLOps Fundamentals
Learn to deploy and monitor models in production.

| Skill | Resource | Priority |
|-------|----------|----------|
| Docker | [Docker for Data Science](https://docker-curriculum.com/) | 🔴 High |
| MLflow | [MLflow documentation](https://mlflow.org/docs/latest/index.html) | 🔴 High |
| Kubernetes basics | Intro course only | 🟡 Medium |
| CI/CD for ML | GitHub Actions + DVC | 🟡 Medium |

### Cloud Platform Deep Dive
Build on Azure certification with hands-on projects:

- [ ] Deploy a model as Azure ML endpoint
- [ ] Set up automated retraining pipeline
- [ ] Implement model monitoring and drift detection

### Optional: Databricks
Very popular in German enterprise—consider Databricks Lakehouse Fundamentals (free certification).

---

## Phase 4: Job Search & Specialization (Months 19–24)
*July 2027 – December 2027*

### Active Networking
- [ ] Attend 3+ [appliedAI Initiative](https://www.appliedai.de/) events (connects to BMW, Siemens, Infineon)
- [ ] Join [Data Science Munich Meetup](https://www.meetup.com/data-science-munich/)
- [ ] Attend [PyMunich](https://www.meetup.com/pymunich/) monthly
- [ ] Engage on LinkedIn with German market keywords

### LinkedIn Optimization
```
Headline: Data Scientist | PhD Astrophysics | ML & Simulation Expert
         Datenwissenschaftler | ML & Simulation

Summary: 10+ years analyzing terabyte-scale datasets and building 
numerical simulations. Transitioning from academic research to 
industry data science. Expert in Python, statistical modeling, 
and physics-informed machine learning.

Skills: Python, SQL, Machine Learning, Azure ML, PyTorch, 
scikit-learn, Data Visualization, Numerical Simulation
```

### Target Companies (Munich)

| Sector | Companies | Language Req. |
|--------|-----------|---------------|
| **Tech Giants** | Google, Microsoft, Amazon, NVIDIA | English OK |
| **Automotive** | BMW, Audi, Continental, Infineon | Often German B2+ |
| **Deep Tech** | Celonis, inovex, ClimatePartner | Usually English OK |
| **Insurance** | Allianz, Munich Re | Often German B2+ |
| **Research** | Fraunhofer, Max Planck Digital | English OK |

### Salary Expectations (Munich)

| Level | Annual Gross |
|-------|--------------|
| Entry (career changer) | €49,000 – €57,000 |
| Mid-level (2-3 yrs) | €57,000 – €68,000 |
| Senior | €70,000 – €90,000+ |

### Recruitment Agencies
- Hays Technology
- Computer Futures
- Michael Page
- Robert Half

---

## GitHub Portfolio Strategy

### Repository Structure

```
📁 data-science-portfolio/
├── 📂 01-sql-analytics/
│   ├── retail-sales-analysis/
│   └── customer-segmentation/
├── 📂 02-physics-to-industry/
│   ├── hydrosim-predictive-maintenance/    ⭐ Showcase project
│   ├── anomaly-detection-fraud/
│   └── numerical-optimization-supply-chain/
├── 📂 03-deep-learning/
│   ├── image-classification-manufacturing/
│   └── time-series-forecasting/
├── 📂 04-mlops/
│   ├── azure-ml-deployment/
│   └── mlflow-experiment-tracking/
└── 📂 05-domain-projects/
    ├── automotive-sensor-analysis/
    └── insurance-risk-modeling/
```

### High-Impact Projects Leveraging Physics Background

#### Project 1: Physics-Informed Predictive Maintenance
**Concept:** Adapt hydrodynamic simulation methods to model industrial equipment degradation.  
**Tech:** Python, scikit-learn, PyTorch, time-series analysis  
**Appeal:** Automotive (BMW), manufacturing

#### Project 2: Cosmology Anomaly Detection → Fraud Detection
**Concept:** Transfer outlier detection techniques from cosmic surveys to financial transactions.  
**Tech:** Python, imbalanced-learn, isolation forests  
**Appeal:** Insurance (Allianz, Munich Re), fintech

#### Project 3: N-body Methods for Traffic Flow
**Concept:** Adapt particle simulation for autonomous vehicle trajectory prediction.  
**Tech:** Python, numerical methods, visualization  
**Appeal:** Automotive R&D

#### Project 4: HPC Pipeline → Cloud MLOps
**Concept:** Document migration from SLURM-based HPC workflows to Kubernetes/Azure ML.  
**Tech:** Docker, Azure ML, MLflow, GitHub Actions  
**Appeal:** Tech companies, demonstrates industry readiness

### Project Checklist (Each Repo)
- [ ] Clear README with problem statement, approach, results
- [ ] Well-documented code with docstrings
- [ ] Requirements file or pyproject.toml
- [ ] Unit tests
- [ ] Visualizations of results
- [ ] Link to blog post or writeup (optional but valuable)

---

## Certification Priority Order

| Priority | Certification | When | Cost |
|----------|---------------|------|------|
| 1 | Deep Learning Specialization | Month 7-9 | ~€125 |
| 2 | Azure Data Scientist Associate (DP-100) | Month 10-12 | ~€165 |
| 3 | Databricks Lakehouse Fundamentals | Month 14 | Free |
| 4 | Optional: AWS ML Specialty | Month 16 | ~€300 |

---

## German Language Considerations

| Target Employer | Requirement |
|-----------------|-------------|
| Google, NVIDIA, Celonis | English sufficient |
| BMW, Allianz (permanent) | German B2+ often required |
| Startups | Usually English OK |

**Recommendation:** If not already proficient, invest in reaching B1-B2 level:

- [ ] Goethe-Institut course (structured)
- [ ] iTalki tutors (flexible, conversation-focused)
- [ ] Deutsche Welle free resources

---

## Monthly Checklist Template

### Month: _______

**Learning:**

- [ ] Course/certification progress: ___________
- [ ] Hours studied this month: _____

**Portfolio:**

- [ ] GitHub commits this month: _____
- [ ] Project milestones completed: ___________

**Networking:**

- [ ] Meetups/events attended: _____
- [ ] LinkedIn connections made: _____
- [ ] Informational interviews: _____

**Job Search (Phase 4):**

- [ ] Applications submitted: _____
- [ ] Interviews: _____
- [ ] Feedback/learnings: ___________

---

## Key Resources Quick Reference

| Category | Resource | Link |
|----------|----------|------|
| SQL | Mode Analytics | mode.com/sql-tutorial |
| ML | Scikit-learn docs | scikit-learn.org |
| DL | DeepLearning.AI | coursera.org/deeplearning-ai |
| Azure | Microsoft Learn | learn.microsoft.com |
| Practice | Kaggle | kaggle.com |
| Jobs | StepStone | stepstone.de |
| Networking | appliedAI | appliedai.de |
| Meetups | Data Science Munich | meetup.com |

---

## Success Metrics

**End of Year 1 (Dec 2026):**

- [ ] SQL proficiency demonstrated (portfolio project)
- [ ] Deep Learning Specialization complete
- [ ] Azure DP-100 certified
- [ ] 3+ GitHub projects published
- [ ] 1 Kaggle competition completed

**End of Year 2 (Dec 2027):**

- [ ] 6+ polished GitHub projects
- [ ] Active in Munich data science community
- [ ] 50+ targeted job applications
- [ ] Job offer secured 🎯

---

*Last updated: January 2026*
