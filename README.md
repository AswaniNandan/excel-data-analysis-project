# Fleet Equipment Data Analysis (Excel Project)


- Project Overview 
This project focuses on cleaning fleet equipment inventory data using Microsoft Excel.


- Dataset
The dataset contains information about equipment across different departments, including equipment class and count.


- Project Workflow
  - Raw data collection
  - Data cleaning


- Data Cleaning Steps
  - Column widths: Sorted the widths of all columns so that the data is clearly visible in all cells.

  - Empty rows: Used the Filter feature to look for blanks and removed all empty rows from the data  - (Rows 8,23,37,48,49).

  - Duplicate records: Used the Conditional Formatting and Remove Duplicates feature to look for and remove any duplicated records from the data.

  - Spelling: Checked for errors in the spelling. Corrected the following texts - (VehicleEquipment, Rehabilitation, Enviromnental, Servcies, Recsue)

  - Whitespace: Used the Find and Replace feature to remove all double-spaces from the data.

  - Department names: The department names didn’t import correctly and they are now split over two columns in the data. Used Flash Fill to reduce the department      names to just one column, and then remove any unnecessary columns or removed duplicate column (Department.1)

  - Bold Letters:- Formatted all column headings with bold letters.



- Files in this Repository:-
     - raw_fleet_equipment_data.csv → Original raw dataset
     - cleaned_fleet_equipment_data.xlsx → Cleaned data


- Tools Used:- 
     - Microsoft Excel






