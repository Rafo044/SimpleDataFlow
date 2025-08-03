# simply_ETL Pipeline Steps

This is simple description of ETL pipeline for this project.

## 1. Extract step

- Scan current folder for CSV, JSON and XML files  
- Read data from each file type using different functions  
- Combine all data to one big DataFrame  

## 2. Transform step

- Convert height from inches to meters (1 inch = 0.0254 meters)  
- Convert weight from pounds to kilograms (1 pound = 0.45359237 kg)  
- Round values to 2 decimal points  

## 3. Load step

- Save the transformed DataFrame to CSV file called `transformed_data.csv`  

## 4. Logging

- Each phase (extract, transform, load) is logged with timestamp to `log_file.txt`  
- Helps to track progress and debugging  

---

You can run the ETL by executing `etl.py` script in terminal.

