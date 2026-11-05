# PPMI-Prodromal-Neuronal-Alpha-synuclein-Project
Contains R code for the "Cognitive Performance in Prodromal Neuronal α Synuclein Disease" paper using PPMI data.

Table of Contents
1.	Introduction
2.	Software 
3.	File Instructions
4.	Acknowledgements 
5.	Disclaimer
 
## 1.Introduction

The purpose of this document is to provide guidance to assist a third-party researcher in understanding the organization and presentation of the statistical analysis code.

The shared code was created to perform analyses for the article "Cognitive Performance in Prodromal Neuronal α‑Synuclein Disease".  This code was created to analyze data accessed from the PPMI database (RRID:SCR_006431) on May 11, 2026. As the PPMI database is always evolving, it is possible that the code may not work if the database has changed since the date the code was created. 

Analytic datasets are not included in the submission.  Researchers can request access to PPMI data at the PPMI Study website (https://www.ppmi-info.org/access-data-specimens/download-data). 

## 2.	Software 
The shared code was written using RStudio 2026.10.1, R version 4.6.1. 

## 3.	File Instructions 
The following files are included with the submission:

•	“PPMI Prodromal Import and Analysis.Rmd” (11/5/2026)

### 3.1 “PPMI Prodromal Import and Analysis.Rmd”
This imports the datasets, readies them for analysis, performs the analysis and creates summary tables and figures.  As an RMarkdown file, this file can be run to create an .html file (or .docx or .pdf) summarizing the analysis. 

The script requires the following dataset:

•	PPMI curated internal data cut (example: “PPMI_Curated_Data_Cut_INTERNAL_YearMonthDay.xlsx”)

The script also requires cognitive assessment datasets for each of:

•	Benton Judgement of Line Orientation (example: “Benton_Judgement_of_Line_Orientation_DayMonthYear.csv”)  
•	Clock Drawing  
•	Hopkins Verbal Learning Test  
•	Letter-Number Sequencing  
•	Lexical Fluency  
•	Modified Boston Naming Test  
•	Modified Semantic Fluency  
•	Montreal Cognitive Assessment  
•	Symbol Digit Modalities Test  
•	Trail Making A and B

By default, the PPMI curated data cut file is assumed to be in the default working directory.  The cognitive assessments should be placed in a folder containing only them.  The location of the cognitive assessments must be specified in the RMarkdown file (by default listed as “C:\Example directory\Cognitive assessments”).

## 4. Acknowledgements 
Codes are shared in compliance with the open access policy for Aligning Science Across Parkinson’s (ASAP) (https://parkinsonsroadmap.org/open-access-policy/). 

## 5. Disclaimer 
Manuscript authors will not provide assistance in the use of the shared code. If a potential error is found in the shared code, please contact the lead author. 
