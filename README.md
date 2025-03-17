# Reading-and-Processing-Monthly-Temperatures-
This lab introduces the use of structs to store related data, file I/O for reading external data, and  arrays for managing multiple records. Students will also learn to work with GitHub for version  control, making meaningful commits as they complete the lab.
Lab Assignment Instructions:

Step 1: Define the Struct 
---------------------------------------------------------
1. Create a struct named TemperatureRecord with two integer fields:
   - day (stores the day number: 1-31)
   - temperature (stores the temperature in degrees Fahrenheit)
2. Declare an array of TemperatureRecord structs.
3. Declare this struct in the global section.

Step 2: Read Data into an Array of Structs 
--------------------------------------------------------------------------
1. Modify the readTemperatures function to:
   - Open temps.txt.
   - Read the day and temperature into an array of TemperatureRecord structs.
   - Use a while loop to read two integers per line (day and temperature).
   - Ensure no more than 31 records are stored.

Step 3: Print Data 
--------------------------------------------------
1. Implement printTemperatures to print all stored temperatures in a formatted table.

Step 4: Compute the Average Temperature 
------------------------------------------------------------------------
1. Implement findAverage to calculate and return the average temperature.

Final Commit & Submission:
--------------------------
1. Ensure all functions are working.
2. Fix any issues.
3. Push final changes to GitHub: "Formatted output and finalized program".

How to Compile and Run:
-----------------------
1. Place all files in the same directory.
2. Compile the C++ file using: g++ main.cpp -o main
3. Run the program: ./main

