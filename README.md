Tutor Allocation Problem
==============

These files are a solver to the Tutor Allocation Problem (TAP) using FICO® Xpress Optimization.

To run the solver, download the .mos file and the three .dat files. The solver is run through the .mos file but we have uploaded the following files for ease of interpreting our results and for data extraction and generation:

***Results:***

Allocate.csv: Contains the information on which tutor has been allocated to which workshop.

CourseIDWorkshops.csv: Contains the corresponding course code for the workshop number.

StartEnd.csv: Contains the information on the start and end time and day of the week for each workshop.

***Data extraction and generation:***

Courses-data.ipynb: Python code to extract the necessary information from the university's DRPS site, and produce the Courses_data.dat file.

courses_data.csv: The extracted courses data in csv form with the disicplines that make up each course, their difficulty, .

Days_tutor.csv: The extracted courses data in csv form with the workshop timetable.

GenerateTutorData.ipynb: Python code to create the necessary dat files: TutorComp.dat and TutorPref.dat
