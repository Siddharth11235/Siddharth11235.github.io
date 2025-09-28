---
layout: single
title: "Resume"
permalink: /resume/
author_profile: false
sidebar: false         # kill left nav on this page
toc: false
classes: [cv, wide]    # our hooks

---

# Siddharth Agarwal
Leuven, Belgium · +32 456 149 084 · siddharthagarwal1993@gmail.com · [LinkedIn](https://www.linkedin.com/in/siddharth-agarwal-1990b576/) · [GitHub](https://github.com/Siddharth11235)

---

## Summary
I am a systems engineer with experience across data platforms and applied ML. I build reliable ETL/lakehouse systems, productionize research code, and design algorithms when needed. Strong in distributed systems, ETL, computer vision and GPU programming. Pragmatic about privacy, observability, and developer ergonomics.
---

## Core Strengths
- **Data Engineering:** Lakehouse design (Delta), batch/stream ETL, schema/versioning, data quality loops, orchestration (Argo), K8s operations, infrastructure as code (Terraform/Helm), cost/performance tuning.  
- **ML & CV:** PyTorch, classical CV, feature pipelines, evaluation/ops, C++ acceleration; comfortable turning notebooks into services/jobs.  
- **Platform:** Azure (Databricks, Functions, Storage), AWS (S3, ECR, EKS), Linux/Docker, Git/CI/CD, SQL (Postgres, SQL Server), Python/PySpark/Polars.  

---

## Experience

**Lynxcare Clinical Informatics NV — Data Engineer**  
*Jan 2025 – Present · Leuven, BE*  
* Built a structured data upload library on Databricks (Spark + Delta) with validation contracts and feedback to annotators/CDM team (GDPR-aware).  
* Implemented event-driven ingestion with Azure Functions; standardized Terraform/Helm/K8s playbooks and documentation; mentored two juniors.  
* Designed a federated analytics platform combining K8s/Argo, and DataShield/Opal (R) for privacy-preserving analysis.  
* Hardened OMOP ETL workflows (Spark Operator on K8s), adding run configs, retries, and observability (logs/metrics).  

**Ivex NV — ML Engineer (Autonomous Driving)**  
*Aug 2021 – Sep 2024 · Leuven, BE*  
* Owned ETL for multi-TB driving data on K8s (Argo on AWS), with schema design in Postgres and export APIs (FastAPI). 
* Built fixed camera 3D perception system
* Built scenario categorization algorithms; product owner for the scenario export tool; mentored a junior engineer.  
* Improved pipeline reliability and artifact lineage; reduced manual operations by templating workflows and Helm charts.  

**Hopstack — Data Scientist (CV) → ML Engineer**  
*Jun 2020 – Aug 2021 · Bengaluru, IN*  
* Shipped on-prem CV pipelines (+32% speedup); set up CI/CD for edge nodes (–40% deploy time).  
* Wrote a C++ trajectory checker; built analytics over TB-scale industrial data (+17% efficiency across 8 facilities).  

**FOSSEE, IIT Bombay — Research Assistant**  
*Feb 2017 – Sep 2019 · Mumbai, IN*  
* Led the **FOSSEE Optimization Toolbox** (C++/Scilab; 32.5k+ users).  
* Contributed to OpenModelica HIL toolboxes; taught the FOT workshop (ORSI 2018).  

**Jet Stream Electric — Product Researcher**  
*Jul 2015 – Oct 2016 · Mumbai, IN*  
* Aircraft design/modeling (MATLAB/ArduPilot) and power station design optimization.  

---

## Selected Projects & OSS
- **OMOP ETL on K8s:** Helm-ized Spark Operator + Argo CronWorkflows; config-driven runs; Delta tables; recovery semantics.  
- **Databricks Ingestion Kit:** Declarative contracts, DQ checks, annotator feedback loop, GDPR logging.  
- **Amazon_Book_Reviews (20M rows):** Batch pipeline, DuckDB/Delta, Argo on K8s; local/dev + cloud deployment.  
- **FOSSEE Optimization Toolbox:** Maintainer; numerical optimization in Scilab/C++.  
- **Functorch Contribution**, **Redis-style Store in C**, miscellaneous performance tooling.  

---

## Skills (Abridged)
- **Languages:** Python, C++, SQL, Bash; some Node.js.  
- **Data:** Apache Spark, PySpark, Delta Lake, Databricks, Polars, Kafka (basics).  
- **Orchestration/Cloud:** Kubernetes, Argo, Helm; Terraform; Azure (Functions, Storage, Databricks), AWS (S3, ECR, EKS), GCP (light).  
- **Storage/DB:** Postgres, SQL Server, CosmosDB, S3/ABFS; DuckDB; Parquet/Delta/Iceberg (exp).  
- **ML/CV:** PyTorch, scikit-learn, OpenCV; evaluation pipelines; model packaging.  
- **Ops:** Docker, CI/CD, logging/metrics, Linux.  

---

## Education
**M.Sc., Artificial Intelligence**, KU Leuven — 2019–2020  
Thesis: *“Singing Songs with AI.”*  

**B.E., Mechanical Engineering**, Gandhinagar Institute of Technology — 2011–2015  

---

## Highlights / Impact
- Sped up CV pipelines by **32%**, cut deploy time **40%**, improved industrial efficiency **17%** (Hopstack).  
- Scaled autonomous-driving ETL on K8s/Argo; shipped export APIs and data models used daily by downstream teams (Ivex).  
- Introduced contract-first ingestion, privacy-aware DQ, and federated analytics primitives (Lynxcare).  

---

## Extras
- Mentoring, code reviews, and “paved road” docs for Spark/K8s newcomers.  
- Compliance mindset (GDPR), reproducible runs, and disaster-recovery drills (backups/restore testing).  
