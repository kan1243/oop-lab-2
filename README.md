# Lab overview
This lab is about how to change code from function form into oop form.By giving all the main code
and dataloader class and fill in the table class that missing.

## Project Structure
-README.md                  #this file
-Cities.csv                 #the dataset
-data_processing.py         #the analysis code

## Design Overview
The 'DataLoader' class
-create Basepath
Initialize the DataLoader with a base path for data files.
-load_csv
Load a CSV file and return its contents as a list of dictionaries.

The 'Table' class
-create table
Intialize the table with name of variable and a viariable that contain list of dict
-convert
try to convert data that in dict to float if it can. Or else return the same data.
-filter
use to filter data in the row that have the same as given condition and return in a new table.
-aggregate
use to compute average,min/max from the fallowing function


## How to test and run code
run the code in terminal to test that there are no error in the code.