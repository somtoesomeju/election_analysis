# election_analysis

## Overview of Project 
In this project, I am helping Tom and Seth perform an audit on election results in Colorado. Tom and Seth are election officials. From the data we are going to derive the total number of votes, the percentage of votes by the county, and the winner of the election.

### Purpose
The purpose of this project is to visualize how we can use python to extract and read data. This is done using the software: Visual Studio Code.

## Background
Working with the csv file which had the complete election results, I created a python script that can loop through the data and produce the election results for each county. Using for loops, the intepreter was able to produce the final outcome of the election.  

# Resources
- Data source: election_results.csv
- Software: python 3.8.8, Visual studio code 1.38.1

## Results
After completing the analysis, the final results were as follows:
- The total number of votes from all counties was 369,711.
- Denver county had the highest voter turnout. 
- The percentage votes for all 3 counties were 10.5% (38,855) for Jefferson, 82.8% for Denver (272,892) and 6.7% (11,606) for Araphoe county.
- With the highest number of votes (272,892), Diana Degette won the election. She had 73.8% of the votes.
- Charles Casper Stockham finished as the runner up with 23.0% (85,213) of the votes. Raymon Anthony Doane finsihed last with 3.1% (11,606) of the votes. 

## Summary
The election data could have been analyzed and tallied in excel to produce similar results. However, using VS code I was able to demonstrate how to get the results using the python langauge. This type of analysis can be performed with any type of data for any election, as long as the csv is imported into the script. Using the "import" function the file can be declared as a variable and opened in VS code. An example would be for if we were trying to analyze the data for a spreadhseet named "party_results.csv". Lets say for instance, this csv sheet contains the election winner by political party and we are trying to analyse the result. 

A script that would be able to import the spreadsheet into our python terminal would look as follows

      import csv
      import os
      
      file_to_load = os.path.join("Resources", "party_results.csv")
      file_to_save = os.path.join("analysis", "election_analysis_by_party.txt")
      
   (note: we need to create a folder to store our data like the "resources" and "analysis" folders above).

The first variable "file_to_load" will connect the "party_results.csv" sheet into our terminal. The second variable "file_to_save" prints out our results in a text file. Declaring both variables allow us to access the spreadsheet. Using the python intepreter we would be able to work with our data and produce results. 
