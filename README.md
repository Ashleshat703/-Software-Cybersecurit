## Features

- Software inventory filtering and cleanup
- Unique CPE vendor extraction
- CPE assignment for software entries
- CVE data loading into SQL Server
- SQL-based vulnerability data handling

## Tech Stack

- Python
- Pandas
- NumPy
- SQL Server
- pyodbc

## Workflow

1. Extract unique CPE vendors
2. Filter and normalize software inventory data
3. Assign likely CPE values to software
4. Extend and organize matched lists
5. Load CVE records into SQL Server
6. Perform SQL-based analysis

## Important Files

```text
SoftwareCPE-CVEMatcher/
|-- UniqueCPEVendorList.py
|-- SoftwareFilter.py
|-- CPEAssigner.py
|-- ListExtender.py
|-- CVELoader.py
|-- Code.sql
|-- README.md
Getting Started
Clone or download this repository
Install required Python dependencies
Configure input file paths and SQL Server connection
Run the scripts in the intended order
Use Cases
Vulnerability management
Software inventory normalization
CPE and CVE mapping
Security data preparation for analysis
Future Improvements
Add configuration file support
Improve portability of file paths
Add requirements documentation
Build a reporting dashboard for CVE matches
Author
Created as a cybersecurity data processing project for software inventory analysis and vulnerability mapping.
