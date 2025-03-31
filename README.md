Tutor Allocation Problem
==============

These files are a solver to the Tutor Allocation Problem (TAP) using FICO® Xpress Optimization.

To run the solver, download the .mos file and the three .dat files. The solver is run through the .mos file but we have uploaded the following files for ease of interpreting our results and for data extraction and generation:

Results:
Allocate.csv: Contains the information on which tutor has been allocated to which workshop.
CourseIDWorkshops.csv: Contains the corresponding course code for the workshop number.
StartEnd.csv: Contains the information on the start and end time and day of the week for each workshop.

Data extraction and generation:
Courses-data.ipynb: Python code to find out the necessary information from the university's DRPS site.
courses_data.csv: The extracted data in csv form
Days_tutor.csv: 
