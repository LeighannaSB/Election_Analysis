# Election_Analysis
Python election analysis project

## Project Overview
The goal of this project is to complete an audit of a recent local election. The tasks were to:
1. Calculate the total number of votes cast
2. Calculate the total number of votes each candidate received
3. Calculate the percentage of votes each cadidate received
4. Determine the winner of the election
5. Calculate the voter turnout for each county
6. Calculate the percentage of votes from each county of the total vote count
7. Determine the county with the highest voter turnout

## Project Summary and Results
By importing the election data CSV into Python we were able to complete all the requested tasks above and write up the election results in a text file.
The following code was used to import the CSV data:
![image](https://user-images.githubusercontent.com/107161421/176808812-d063aa47-13c9-4108-a992-a087e8eb3ea6.png)

The following code used *if* statements inside a *for loop* to the votes for each candidate and county:
![image](https://user-images.githubusercontent.com/107161421/176809321-e66249c4-b24d-4e44-8ece-02adcb10e09f.png)

*For loops* were also used to calculate the candidates and counties percentage of votes:
![image](https://user-images.githubusercontent.com/107161421/176809531-9490c712-21d1-4d49-8f24-b999af6d0ea9.png)
![image](https://user-images.githubusercontent.com/107161421/176809594-f42a1c37-2735-4e91-b53f-91c0ab2b610d.png)

We were able to successfully confirm there were 369,711 total votes cast in the election and the winner of this election was Diana DeGette with 73.8% of the votes (272,892 total votes).  We were also able to confirm the county with the highest voter turnout was Denver County with 82.8% of the votes (306,055 votes). 

The full election results and all of the final calculations from the election committee's requested tasks were printed in the terminal and written to the Election Analysis text file. 
![image](https://user-images.githubusercontent.com/107161421/176810213-90d7a157-d753-4113-8425-97e5de5f68d5.png)
![image](https://user-images.githubusercontent.com/107161421/176810268-ef113e85-b54d-41ee-b08a-f7198d37c14f.png)
