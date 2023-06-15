# Script For Analysis of Data from Mass Spectrometry
A Python script to aggregate multiple mass spec data (from instrumentation) and output an Excel file.

Pharmaceutical company had a problem of needing to process a lot of test data. Their current solution involved manually going into each data file, searching if a specific value(s) existed or not, plugging it into a specific formula, and compiling it into a central file/spreadsheet. I built a script to automate these set of procedures. This resulted in greatly speeding up analysis of the test datasets. This script reduced a 5 minute error prone task to be done in seconds. Lab members ran hundreds of tests and saved a lot of time and labor. With this script, the company was able to identify which chemical additions were promising and was able to move onto the next phase to scrutinize them further. 

This script made use of the Python library Pandas.

I tried to make it so that the end-user who is not familiar with programming can use it and make modifications easily. 

There are five files in this folder:
 * "TheScript - JC Parent v2" is the code in both Jupyter notebook and html format, 
 * "relationalValues.csv" is the lookup table to be edited, 
 * and "analysis.xls" file is the output where it consolidated all the Excel files in a certain directory. In this case, it consolidated 8 files.

The raw data files are from a mass spectrometer. I have not uploaded these raw data files. I have changed the original code names to fake/made up code names.

Please view the Python code from the Jupyter notebook if viewing directly on Github or download the html file and open it in a browser of your choice.
