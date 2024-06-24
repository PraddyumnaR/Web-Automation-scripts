# Web Automation Scripts

This repository contains web automation scripts for performing specific tasks on particular websites. The scripts are written in Python and utilize web automation libraries to automate interactions with web pages.

## Scripts

### 1. CancerVar Automation Bot

The CancerVar Automation Bot is a Python script that automates the process of uploading gene names/symbols to the CancerVar website, querying by HGNC gene symbol, and retrieving the results. The results are saved in an Excel format for further analysis.

#### Features

- Uploads gene names/symbols to the CancerVar website.
- Uses default settings for querying.
- Queries by HGNC gene symbol.
- Retrieves and saves the results in an Excel file.

#### Requirements

- Python 3.x
- Selenium
- Pandas
- Openpyxl

#### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/PraddyumnaR/Web-Automation-scripts.git
   cd Web-Automation-scripts
2. Create a virtual environment and activate it:
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
4. Usage
   Ensure you have the Chrome browser installed and the ChromeDriver executable available in your system's PATH.

   Prepare a text file (genes.txt) with a list of HGNC gene symbols, one per line.

5. Run the script:
   ```bash
   python cancervar_automation_bot.py

The script will automatically upload the gene names, perform the query, and save the results in an Excel file named cancervar_results.xlsx.

Example
Here is an example of how to use the CancerVar Automation Bot:

Create a file named genes.txt with the following content:

TP53
BRCA1
EGFR

6. Run the script:
  ```bash
  python cancervar_automation_bot.py

Check the current directory for the file cancervar_results.xlsx containing the query results.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
The script makes use of the Selenium library for web automation.
Data is processed and saved using Pandas and Openpyxl.

Feel free to contribute to this repository by opening issues or submitting pull requests.





