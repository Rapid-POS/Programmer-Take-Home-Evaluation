# Programmer-Take-Home-Evaluation
This document will list the steps a candidate for the Programmer I position will perform to evaluate skill level, proficiency, and ability to deliver a solution meeting the requirements in a timely manner.

# Tasks:
- Download and install Microsoft SQL Server 2016 Express (if not already installed)
- Unzip the “DemoGolfDatabase.7z” file
- Attach the MDF & LDF files as database “DEMOGOLF”
- Create a trigger on the AR_CUST table to add an entry in the AR_CUST_NOTE table whenever an existing entry in the AR_CUST table is modified.  The content of the note should include the date/time of the change and a brief, appropriate note.
- Create a stored procedure to accept inputs of @START_DATE and @END_DATE and output select, pertinent details from the PS_TKT_HIST and PS_TKT_HIST_LIN tables to show sales, quantity sold, taxable sales, non-taxable sales, cost, and regular price.  The data should be grouped by date and store, showing one row for each date/store.
- Create a .exe program (using C# in the IDE of your choice) that executes the stored procedure from the previous step, serializes the output into JSON, and stores the output into a file.  The file should include a fields added that shows the profit for each row.  If you do not have an IDE of choice, our recommendation is Visual Studio trial edition.
- The deliverable to return is:
  - A full backup of the database, archived with 7-zip (.7z extension)
  - Name of the trigger created
  - Names of the stored procedure created
  - Packaged .exe code
  - Result file
- Place the results in a Reposority on your GitHub account along with a ReadMe containing your full name and which method or job site you used to reach this repository.  Send an invitation to this repository Rapid POS at: recruiting.programmer@rapidpos.com.
