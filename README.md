# Reverse Scorecard Generation

Combine column-major HHS Zero Trust Scorecard Excel spreadsheets into a row-major CSV file.

Steps to use the script:
1. `cd` into the repo folder.
2. Install dependencies: `pip install -r requirements.txt`
3. Put Excel files in the `input_files` folder.
4. Run the script: `python script.py`.
5. The script will generate a `out.csv` file. OR, you can put an existing `out.csv` file in the repo folder and the script will append new roles to the CSV file (it will not overwrite existing rows).
