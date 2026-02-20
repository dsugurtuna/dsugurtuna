# Ugur Tuna

**Senior Data Scientist | NIHR BioResource, University of Cambridge**

I build production-grade bioinformatics pipelines, machine learning systems, and cloud-native platforms that turn genomic data into actionable research outcomes. At Cambridge, I lead end-to-end genomic data provisioning for one of the UK's largest national research cohorts — processing 50,000+ samples, managing terabyte-scale secure transfers, and enabling precision recall-by-genotype studies across rare diseases, immunology, neurodegeneration, and inflammatory bowel disease.

---

## What I Do

- **Clinical Bioinformatics** — HLA imputation pipelines (SNP2HLA/Beagle) at 50K+ sample scale, APOE genotyping, GWAS data preparation, multi-platform variant search across 7 genotyping arrays, and genomic QC for WGS/WES/array data
- **Machine Learning & AI** — Fraud detection with CatBoost (value-weighted loss, isotonic calibration), demand forecasting at 600K+ SKU scale (LightGBM/TFT/N-BEATS ensemble with 150+ engineered features), computer vision invoice digitization (YOLOv5), and clinical NLP phenotyping (SciSpacy + ConText)
- **Cloud-Native Platform Engineering** — Microservices on Kubernetes (v1.28) with Terraform-provisioned AWS infrastructure (EKS, RDS, ElastiCache, KMS), Docker containers across 17+ services, zero-trust NetworkPolicies, and Prometheus monitoring
- **Data Governance & Compliance** — GDPR Subject Access Request automation, Five Safes Framework implementation, GPG-encrypted secure transfers with SHA-256 verification and full audit trails

---

## Technical Stack

**Languages:** Python, R, Bash/Shell, TypeScript, SQL, AWK, HCL (Terraform)

**Bioinformatics:** PLINK 1.9/2.0, BCFtools, SNP2HLA, Beagle, CookHLA, SciSpacy, NCI LDlink API

**ML/AI:** CatBoost, LightGBM, PyTorch, YOLOv5, scikit-learn, spaCy, GPT-4V/LLaVA integration

**Frameworks:** FastAPI, Pydantic v2, React 18, TanStack Query, Recharts, Plumber (R), Tidyverse

**Infrastructure:** Kubernetes, Terraform, Docker, GitHub Actions, NGINX, Prometheus, MLflow, Airflow, Redis

**Cloud:** AWS (EKS, RDS, ElastiCache, KMS, VPC, S3), Azure (AzCopy, Aridhia SDE)

---

## Featured Projects

### [gut-reaction-platform](https://github.com/dsugurtuna/gut-reaction-platform)
Production-grade 6-microservice clinical research platform with NLP phenotyping (SciSpacy), visual PII auditing (GPT-4V/LLaVA), NHS Trust data harmonization, React dashboard, and full Kubernetes/Terraform infrastructure.

### [fraud-detection-system](https://github.com/dsugurtuna/fraud-detection-system)
Value-weighted fraud detection pipeline with CatBoost gradient boosting, expected-value regression, isotonic calibration, m-estimate risk encodings, and business-aligned evaluation metrics.

### [retail-demand-forecasting-at-scale](https://github.com/dsugurtuna/retail-demand-forecasting-at-scale)
Enterprise ML pipeline for 600K+ SKU demand forecasting using a LightGBM/TFT/N-BEATS ensemble, 150+ engineered features, custom WRMSSE objective, Airflow DAGs, and MLflow tracking.

### [british-invoice-digitization](https://github.com/dsugurtuna/british-invoice-digitization)
Computer vision pipeline for automated invoice field extraction using YOLOv5 with 6-class detection, thread-safe model serving via FastAPI, and hot-reload model management.

### [hla-pipeline-manager](https://github.com/dsugurtuna/hla-pipeline-manager)
End-to-end HLA imputation orchestration for 50,000+ biobank samples — 7-step pipeline with PLINK, SNP2HLA, Beagle, AWK hash-map ID conversion, and 8-locus clinical typing report generation.

### [clinical-cohort-selector](https://github.com/dsugurtuna/clinical-cohort-selector)
Precision medicine toolkit for genotype-stratified participant recall with demographic balancing, age-band stratification, and sex-matched control design for clinical studies.

---

## Professional Impact

- Processed **50,000+ samples** across HLA imputation batches with automated strand-conflict resolution
- Delivered genomic cohorts of **10,732 samples** with cryptographic verification
- Managed **777 GB** secure cloud data transfers to research environments
- Harmonized clinical data from **4 NHS Trust** formats into OMOP CDM
- Led a team of **6 junior data scientists** in genomic data processing and secure data handling
- Enabled research across **10+ disease areas** including rare diseases, IBD, neurodegeneration, and immunology
- Supported **45 GDPR Subject Access Requests** returning clinical genomic data for patient care decisions

---

## Engineering Philosophy

Every repository follows consistent engineering standards: structured Python packages with `pyproject.toml`, comprehensive test suites, Docker containers, CI/CD via GitHub Actions, Makefile automation, and detailed documentation. Legacy shell scripts are preserved alongside modern Python rewrites to demonstrate the evolution from ad-hoc tooling to production-grade software.

No real participant data, credentials, or proprietary information is committed — all repositories use synthetic data and mock responses, demonstrating data sensitivity awareness and testability.

---

*Cambridge, United Kingdom*
