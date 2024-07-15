## Roadmap

- [x] Install libraries (Pandas, SQLite, PySpark)
- [x] Load the data from all sources
- [x] Datasets Overview (Columns, Rows, Types, NAs, etc.)
- [ ] Summarize the transformations to be done to construct each table
- [ ] Table Person (Python)
  - [ ] Implement a high-level function that applies transformations on data.
  - [ ] Implement transformation functions and transformation rules.
- [ ] Table Care Site (SQL)
  - [ ] Write SQL queries to create and fill the table.
  - [ ] Write the Python code to execute the queries
- [ ] Table Provider (PySpark)
  - [ ] Configure Spark and get it running
  - [ ] Define the transformations and create a new table.
- [x] Generate requirements.txt, and Readme run guide.

## Installation / Run guide

1. Requirements:

   - Python version : 3.12.2
   - Spark installed on your device.

2. Install dependencies and add virtual environment to the Python Kernel:

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
