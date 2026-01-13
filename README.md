## Medicare Risk Adjustment–Style Data Processing & Submission Pipeline (SAS 9.4)

### Project Overview
This project simulates an end-to-end Medicare Risk Adjustment data workflow, demonstrating how raw provider and member data is ingested, validated, reconciled, and formatted into CMS-style submission-ready text files using Base SAS 9.4 (Windows 10).The goal of this project is to showcase practical informatics skills aligned with healthcare data submission requirements, including data quality validation, audit trail documentation, reconciliation, and flat file generation.

### Objectives 

Simulate receipt of raw healthcare data from multiple sources Apply validation rules to ensure data quality and submission compliance Reconcile record counts and document processing steps Generate a submission-ready flat text file aligned with CMS-style formatting requirements Maintain an audit trail to support traceability and compliance

### Data Sources (Mock Data – No PHI)

This project uses synthetic data to replicate real-world healthcare inputs: Member File: Member demographics and enrollment details Provider File: Provider identifiers and specialties Diagnosis File: ICD-10 diagnosis codes linked to members and providersIntentional data quality issues (e.g., missing values, invalid codes, duplicates) were introduced to demonstrate validation and remediation processes.

### Tools & Technologies 

Base SAS 9.4 (Windows 10) SAS DATA Steps & PROC SQL Flat file (.txt) generation CSV ingestion and processing

### Key Processing Steps

#### 1.0 File Ingestion 
Imported raw CSV files into SAS datasets Verified structure and completeness prior to processing

#### 2.0 Data Validation 
Implemented rule-based validation checks including:   Missing member identifiers   Invalid ICD-10 code formats   Future or out-of-range service dates   Missing provider identifiers Isolated non-compliant records for remediation

#### 3.0 Data Cleansing & Reconciliation
Removed invalid records from submission datasets Reconciled record counts between raw, clean, and error datasets Ensured data integrity prior to submission formatting

#### 4.0 Audit Trail Documentation 
Created SAS-based audit logs capturing:   
File receipt   
Validation completion   
Reconciliation results   
Submission file creation

#### 5.0 Submission File Creation
Formatted validated data into pipe-delimited flat text files Applied standardized date formatting and field ordering Generated submission-ready output suitable for external transmission

#### Output 
Submission-ready text file formatted according to defined specifications Validation error datasets Reconciliation summaries Audit log documenting the full data lifecycle

#### Project Structure 
Risk_Adjustment_Data-Workflow-MEDICARE

SAS_Project/

├── raw_files/

├── sas_programs/

├── output/

├── audit/

└── README.md


#### Key Skills Demonstrated

SAS-based data retrieval, validation, and formatting Healthcare informatics workflows Compliance-focused data processing Attention to detail and quality assurance Audit readiness and documentation CMS-style submission preparation

#### Disclaimer
All data used in this project is synthetic and anonymized. No real patient or provider information is included. This project is intended solely for educational and portfolio demonstration purposes.

#### Contact
For questions or professional inquiries:

linkedin: 
