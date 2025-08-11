## Introduction
In this project, I created a simple ETL data pipeline to work with different types of datasets. The pipeline takes the data, changes it into a clean format, and saves it as CSV files. All steps of the process are written into a log file, so it is easy to follow what happened and fix problems if needed.

## Data Flow
<img src="./SimpleDataFlow /image/SimpleDataFlow.png" alt="Data Flow" width="100%">

## Folder Structure
```markdown
SimpleDataFlow/
│
├── data/                  
│   ├── raw/               
│   └── processed/         
│
├── logs/                  
│   └── log_file.txt
│
├── docs/ 
│   └── index.md
│
├── src/                     
│   └── etl.py
│
├── requirements.txt       
├── README.md              
├── mkdocs.yaml
└── LICANSE      

```
