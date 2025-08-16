# Calculate Bank's Total Monthly Deposit

## Objective  

An automation that calculates the total monthly deposit of a bank from an Excel file and store the output in a new sheet.

## Process Map
<img width="1019" height="144" alt="image" src="https://github.com/user-attachments/assets/82e51dac-532a-4d47-9e94-14eff71ec777" />

## Project Information 

We use workbook activities such as read range when automating simple actions using an excel file. The workbook activities do not open excel, and they can read excel files even on a machine that does not have excel installed. We build the data table using a build data table activity, and we create the columns within that activity. We use the Excel Process Scope, Use Excel file, and For Each Excel Row to iterate through the active excel file. We can add a row to a data table using the the Add Data Row activity, in this project we add a row by creating an ArrayRow with the values to be added. 
 
## Development Objectives 

- Download the Excel file given for practice 

- The file contains three deposit categories – Cash In, On-Us Check, and Not On-Us Check 

- Calculate the total amount received in all three categories for June 

- Store calculated values in a new sheet in the same excel file 
