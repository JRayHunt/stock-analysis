# stock-analysis
This project will be to analyze a set of green energy stocks

## Overview of Project
In this project we refactored code. This means we changed the code to make it run more efficiently without changing functionality.

### Purpose
In our project we analysed as selection of green energy stocks to determine which stocks were better in terms of total volume (how many times the stock was traded in the year) and annual rate of return. For easy reading, we used conditional formatting to make the annual rate of return green for positive and red for negative.

## Analysis
### Explanation 
In this project we used indexes and "for loops" to iterate through records of stocks for the years 2017 and 2018. The best stocks for 2018 were ENPH and RUN.

### Challenges
The loops were the most difficult part of this project. Trying to get the tickerIndex variable to work properly so that the arrays were synched up  was especially challenging. To solve this I utilized office hours on Friday night and frequented the Slack threads. It really helped seeing how fellow students were approaching the problems.

## Summary
### Executin Results
Refactoring the code resulted in the execution time for the script for 2017 from 0.1757813 to 0.2109375. As shown in ![VBA_Challenge_2017.png](/Resources/VBA_Challenge_2017.png)

Refactoring the code resulted in the execution time for the script for 2018 from 0.1132813 to 0.1289063 as shown in ![VBA_Challenge_2018.png](/Resources/VBA_Challenge_2018.png)

### Refactoring Results
So for both 2017 and 2018 the execution time increased. This may be due to using too many for loops or too many arrays. Even though the code ran slower the refactoring was still worth it because the code is more flexible and easier to maintain.

