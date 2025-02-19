## Roadmap

- [x] Install libraries (Pandas, SQLite, PySpark)
- [x] Load the data from all sources
- [x] Datasets Overview (Columns, Rows, Types, NAs, etc.)
- [x] Summarize the transformations to be done to construct each table
- [x] Table Person (Python)
  - [x] Implement a high-level function that applies transformations on data.
  - [x] Implement transformation functions and transformation rules.
- [x] Table Care Site (SQL)
  - [x] Write SQL queries to create and fill the table.
  - [x] Write the Python code to execute the queries
- [x] Table Provider (PySpark)
  - [x] Configure Spark and get it running
  - [x] Define the transformations and create a new table.
- [x] Generate requirements.txt, and Readme run guide.

## Installation / Run guide

1. Requirements:

   - Python version : 3.12.2
   - Spark installed on your device.

2. Create a virtual environment and add it to the Python Kernel:

   ```console
   python -m venv hdi

   source hdi/bin/activate # Linux
   .\hdi\Scripts\activate # Windows

   python -m pip install --upgrade pip

   pip install ipykernel
   python -m ipykernel install --user --name=hdi
   ```

3. Add the 5 csv files to the data/ folder

4. Run main.ipynb
