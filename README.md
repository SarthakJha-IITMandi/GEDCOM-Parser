# GEDCOM-Parser

A parser in C++ for GEDCOM 5.5.5 Files.

## Current Status

- Import a GEDCOM file into the program
- THe header information will be parsed and displayed
- Added functionality of comments which can be parsed and stored based on req., and ignored from file
- All individuals are parsed and their name, sex and id are displayed.
- Number of individuals is calculated
- Calculate and link individuals to families

## TODO

- Create modes to run based on user
- Calculate ages of individuals during events
- Process errors in file and display them appropriately
- GUI Interface to display families and other data in a readable form

## Future ideas

- Process and correct error on the fly
- Use a database to retrieve information for future calls
- Remove irrelevant and redundant data from the GEDCOM file before parsing
