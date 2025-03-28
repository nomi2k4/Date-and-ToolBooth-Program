Date and ToolBooth C++ Programs

This repository contains two separate C++ programs: one for handling dates and the other for simulating a tool booth.

Date Program

Description

This C++ program takes a day, month, and year as input from the user and displays the date in the format MM/DD/YYYY.

Features

* Prompts the user to enter the day, month, and year.
* Validates the day to be within the range of 1-31.
* Validates the month to be within the range of 1-12.
* Displays the entered date in the format MM/DD/YYYY.

Code Structure

The code consists of the following files:

* main.cpp: Contains the main function, which handles user input and displays the output.
* header.h: Contains the declaration of the Date class.
* implementation.cpp: Contains the implementation of the Date class methods.

The Date class encapsulates the data and functions to manage date values.

Dependencies

* iostream: For input/output operations.

Compilation and Execution

To compile and run the program:

1.  Save the files as main.cpp, header.h, and implementation.cpp.
2.  Use a C++ compiler (e.g., g++) to compile the code:

    g++ main.cpp implementation.cpp -o date_program

3.  Run the executable:

    ./date_program

ToolBooth Program

Description

This C++ program simulates a tool booth, calculating the total number of cars and the total amount of money collected.

Features

* Simulates cars passing through a toll booth.
* Distinguishes between paying and non-paying cars.
* Calculates the total number of cars.
* Calculates the total amount collected from paying cars.
* Displays the total number of cars, total amount collected, and the number of non-paying cars.

Code Structure

The code consists of the following files:

* main.cpp: Contains the main function, which simulates the toll booth and displays the results.
* header.h: Contains the declaration of the ToolBooth class.
* implementation.cpp: Contains the implementation of the ToolBooth class methods.

The ToolBooth class encapsulates the data and functions to simulate the toll booth.

Dependencies

* iostream: For input/output operations.
* string: For using string variables.

Compilation and Execution

To compile and run the program:

1.  Save the files as main.cpp, header.h, and implementation.cpp.
2.  Use a C++ compiler (e.g., g++) to compile the code:

    g++ main.cpp implementation.cpp -o toll_booth

3.  Run the executable:

    ./toll_booth