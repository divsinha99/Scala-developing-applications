# Scala-developing-applications
# Problem Statement-
Connect to database
Host: nn01.itversity.com
Database: hr
Username: hr_ro
Password: itversity
Understand data model
We are interested in only employees table for this demo
Compute commission amount – formula: salary * commission_pct
If commission_pct is not set up, then employee is not eligible for getting commission
Output of the program
first_name: Charles;last_name: Johnson;commission amount:620.0
first_name: Winston;last_name: Taylor;commission amount:Not eligible



To run in sbt:
--------------
sbt "run-main CommissionAmount dev"
