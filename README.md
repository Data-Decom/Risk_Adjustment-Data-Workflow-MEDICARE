## Medicare Risk Adjustment–Style Data Processing & Submission Pipeline (SAS 9.4)

### Objective:
Simulate the end-to-end process of receiving raw provider files, validating and reconciling data, and producing CMS-style submission-ready text files using Base SAS 9.4 with audit documentation.

### Key Skills Demonstrated: 
SAS Base 9.4 Data validation & reconciliation File formatting & text file creation Audit trail documentation Compliance-driven workflows

### Scenario
Incoming diagnosis and member data from multiple providers must be validated, reconciled, formatted, and submitted to CMS for Medicare Risk Adjustment.

### Mock Source Files (CSV → SAS)
Member File (`members.csv`)| memberid | dob | gender | enrollmentdate|

Provider File (`providers.csv`)| providerid | npi | specialty |

Diagnosis File (`diagnoses.csv`)| memberid | icd10 | servicedate | providerid |

### Intentional data issues: 
Missing DOB, Invalid ICD-10 format, Duplicate members, Service date outside enrollment period

