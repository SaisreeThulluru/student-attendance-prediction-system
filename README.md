# Attendance Certification Report Generator

## Overview

This project automates the generation of internship certification reports based on student attendance records.

The program reads attendance data from a CSV file, calculates attendance percentages, determines certification eligibility, and generates a formatted Excel report.

## Features

* Reads attendance data from a CSV file
* Calculates total sessions attended
* Computes attendance percentage
* Determines certification eligibility
* Generates a professional Excel report
* Applies formatting, borders, filters, and column sizing automatically
* Freezes header rows for easier navigation

## Technologies Used

* Python
* Pandas
* OpenPyXL
* Google Colab / Jupyter Notebook

## Dataset Requirements

The input CSV file should contain:

* Name
* Email
* Day_1 to Day_40 attendance columns

Each Day column should contain attendance duration in minutes.

Example:

| Name      | Email                                             | Day_1 | Day_2 | ... |
| --------- | ------------------------------------------------- | ----- | ----- | --- |
| Student A | [student@example.com](mailto:student@example.com) | 120   | 110   | ... |

## Attendance Criteria

* Total Sessions: 40
* Session Duration: 2 Hours
* Minimum Required Attendance per Session: 96 Minutes
* Certification Requirement: 80% Attendance or Higher

## Output

The program generates:

`Internship_Certification_Report.xlsx`

Containing:

* Name
* Email
* Internship Duration Hours
* Total Sessions
* Sessions Attended
* Attendance Percentage
* Certification Status

## Installation

Install required packages:

```bash
pip install pandas openpyxl
```

## Usage

1. Upload the attendance CSV file.
2. Update the file path in the script.
3. Run the Python script.
4. Download the generated Excel report.

## Example Output

| Name      | Attendance Percentage | Certification Status |
| --------- | --------------------- | -------------------- |
| Student A | 90.00                 | Certified            |
| Student B | 75.00                 | Not Certified        |

## Future Enhancements

* PDF report generation
* Email notifications
* Attendance dashboard visualization
* Streamlit web application

## OUTPUT
<img width="1878" height="808" alt="Output" src="https://github.com/user-attachments/assets/4a722816-4d69-4c99-b92f-98f0de80e1f3" />

## Author

**Thulluru Saisree**
B.Tech Artificial Intelligence & Machine Learning (AIML)
VVIT / VVITU
