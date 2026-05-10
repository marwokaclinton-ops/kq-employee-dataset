# Python Data Analytics Project

## Overview

This project demonstrates the use of Python in data analytics through three main tasks
1. Working with JSON data from GitHub
2. Extracting and analyzing data from DummyJSON API endpoints

The project shows how to collect, process, analyze, and save data using Python.

---

## Tools and Technologies Used

* Python 3
* Requests library
* Pandas library
* GitHub (for hosting JSON data)
* DummyJSON API
* Mockaroo (for synthetic data generation)

---

## Project Structure

```
python-data-analytics-project/
│
├── README.md
├── python_article.pdf
│
├── part2/
│   ├── employees.json
│   ├── employees.csv
│   └── github_json_extraction.py
│
├── part3/
│   ├── products.csv
│   ├── carts.csv
│   └── dummyjson_api.py
---

## Part 1: Working with JSON Data from GitHub

### Steps followed:

1. Created a synthetic dataset using Mockaroo
2. Exported the dataset as a JSON file
3. Uploaded the JSON file to GitHub
4. Retrieved the raw GitHub link
5. Used Python `requests` to extract the JSON data
6. Converted JSON data into a Pandas DataFrame
7. Saved the final output as a CSV file

### Output Files:

* employees.json
* employees.csv

### Key Skills:

* API request handling
* JSON parsing
* DataFrame creation
* CSV export

---

## Part 2: Working with DummyJSON API

### APIs Used:

* https://dummyjson.com/products
* https://dummyjson.com/carts

### Steps followed:

1. Sent HTTP GET requests using Python
2. Extracted JSON responses
3. Converted JSON data into Pandas DataFrames
4. Saved structured data as CSV files

### Output Files:

* products.csv
* carts.csv

---

## How to Run the Project

### Step 1: Install required libraries

```
pip install requests pandas
```

### Step 2: Run scripts

```
python github_json_extraction.py
python dummyjson_api.py
```

---

## Learning Outcomes

By completing this project, the following skills were gained:

* Working with APIs in Python
* Handling JSON data
* Data cleaning and transformation
* Data analysis using Pandas
* Saving structured datasets as CSV files
* Using GitHub for data hosting

---

## Author

Clinton Marwoka Onduko

