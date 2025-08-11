## Introduction
In this project, I created a simple ETL data pipeline to work with different types of datasets. The pipeline takes the data, changes it into a clean format, and saves it as CSV files. All steps of the process are written into a log file, so it is easy to follow what happened and fix problems if needed.

## Data Flow
[Data Flow]()










## Folder Structure
SimpleDataFlow/
│
├── data/                  
│   ├── raw/               
│   └── processed/         
│
├── logs/                  
│   └── etl_process.log
│
├── src/                   
│   ├── extract.py
│   ├── transform.py
│   └── load.py
│
├── requirements.txt       
├── README.md              
└── run_pipeline.py        


