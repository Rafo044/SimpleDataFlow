## Introduction
In this project, I created a simple ETL data pipeline to work with different types of datasets. The pipeline takes the data, changes it into a clean format, and saves it as CSV files. All steps of the process are written into a log file, so it is easy to follow what happened and fix problems if needed.

## Data Flow
![Data Flow](https://github.com/Rafo044/SimpleDataFlow/blob/main/docs/image/SimpleDataFlow.png)


## Folder Structure
```markdown

SimpleDataFlow/
│
├── data/
│   ├── json/
│   │   ├── source1.json
│   │   ├── source2.json
│   │   └── source3.json
│   │
│   ├── log/
│   │   └── log_file.txt
│   │
│   ├── processed/
│   │   ├── source1.csv
│   │   ├── source2.csv
│   │   └── source3.csv
│   │
│   └── xml/
│       ├── source1.xml
│       ├── source2.xml
│       └── source3.xml
│
├── docs/
│   ├── image/
│   │   └── SimpleDataFlow.png
│   │
│   └── index.md
│
├── src/
│   └── etl.py
│
├── tests/
│   └── test_etl.py
│
├── .gitignore
├── LICENSE
├── README.md
├── mkdocs.yml
└── requirements.txt


