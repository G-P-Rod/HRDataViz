# HRDataViz
This project generates HR employee statistic reports in PDF format from an Excel data source. It analyzes data by "Pion" (department) and "Obszar kadrowy" (personnel area) and provides insights into employee headcount, positions, salaries, and more.


## Features
Creates separate reports for each unique combination of "Pion" and "Obszar kadrowy".
Categorizes employees as teachers and non-teachers.
Generates pivot tables summarizing employee counts, totals, averages, and medians for different categories.
Formats tables for readability with a custom style.
Includes a descriptive title and logo image on each report.


## Requirements
- Python 3.x
- Python libraries:
    - pandas
    - numpy
    - reportlab (PDF generation)


## Usage
Make sure you have the required libraries installed.
Place your Excel data file (containing employee data) in the data/raw/ directory as a 'data_per_day.xlsx', within the project structure.
Ensure the image used for the logo (bow.png) is located in the graphics directory.
Run the script will generate PDF reports in the data/processed directory, named <Pion>_<Obszar_kadrowy>.pdf.


## Execution
python main.ipynb


## Fonts
The script uses Calibri and Calibri-Bold fonts for the reports. These fonts are not included in the project, so you'll need to install them on your system separately for proper PDF rendering.

## Result
For each unique combination of "Pion" and "Obszar kadrowy" will be created separeted report:

![image](https://github.com/G-P-Rod/HRDataViz/assets/143654189/bea7ce1a-386f-4e1f-bad3-de9d14ffa6d6)

With grouped data for this organizational unit:

![image](https://github.com/G-P-Rod/HRDataViz/assets/143654189/bdeb4ad7-439b-44a9-9bac-f1e305c6a183)

The script informs us what and how many PDF files have been created:

![image](https://github.com/G-P-Rod/HRDataViz/assets/143654189/739b8085-ffba-4a08-8323-fe5c9f68d545)
