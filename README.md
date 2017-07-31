# Top-100-contractors
Created SQLite database with two tables in order to run some queries against the data set.

Downloaded the Excel file from footnote 6 : https://en.wikipedia.org/wiki/Top_100_Contractors_of_the_U.S._federal_government

The Excel file is divided into tabs. The first tab covers all the Federal government while the remaining tabs are by department.

Created SQLite3 database of the department specific actions (contracts) and dollar amounts. It has two tables. The first "contractors" have an id (as a primary key) and a global_vendor_name (as a varchar). The second includes an id (primary key), department, actions (number of actions), dollars (dollars obligated) and contractor_id as a foreign key to the contractors table.

I order to view the html file of the python notebook please go to: 
