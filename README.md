# Rule-Based Data Extraction CLI


<img width="1536" height="1024" alt="ChatGPT Image Jan 12, 2026, 04_47_20 PM" src="https://github.com/user-attachments/assets/29481811-f372-4b87-8c50-d30b3997fdd2" />


## Problem Statement

Semi-structured lab report PDFs contain critical water quality data across inconsistent formats. Manual extraction of 20+ parameters (pH, conductivity, dissolved solids, bacteria counts) is time-consuming, error-prone and doesn't scale as report volumes grow.

## Technical Approach

* Build rule-based parsers using pdfplumber and regex for semi-structured PDF extraction  
* Define field mapping rules for 20+ target parameters across varying report layouts  
* Implement table detection and cell boundary logic for structured data capture  
* Enforce schema validation using Pydantic models with type checking and range constraints  
* Output clean, tab-delimited format for direct Excel paste  
* CLI interface supporting single file and batch processing modes  
* Handle edge cases: multi-page reports, merged cells, inconsistent headers

## Skills

Python · CLI development · pdfplumber · PyMuPDF · pandas · regex · Rule-based extraction · Semi-structured data · Schema validation · Pydantic · Data parsing · Excel integration · Batch processing · argparse/typer

## Challenges & Solutions

* Inconsistent semi-structured layouts → rule-based field detection with fallback patterns  
* Merged table cells breaking extraction → custom cell boundary detection logic  
* Invalid or out-of-range values → Pydantic schema validation with error reporting  
* Parameter name variations → synonym mapping rules for standardised output

## Quantifiable Business Impact

* 95% reduction in manual data entry time  
* more than 90% accuracy in data extraction
* Schema-validated output ensuring data integrity  
* Copy-paste ready format eliminating reformatting steps  
* CLI batch mode enabling scalable multi-file processing

## Client Review
<img width="638" height="428" alt="image" src="https://github.com/user-attachments/assets/de66a4c3-efad-49d5-a3d6-eb33f31c47a6" />

