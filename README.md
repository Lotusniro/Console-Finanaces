# Console-Finanaces

## Description
This is a console application that allows the user to manage their finances. 


first I calculated the total number of months included in the dataset which is the length of the array.
![SCREENSHOTS
](https://github.com/Lotusniro/Console-Finanaces/blob/main/screenshots/Screenshot%202023-12-24%20at%2012.44.34.png)

then we calculate the total amount of profit/losses over the entire period which is the sum of the profit/losses .

- calculated the net total amount of "Profit/Losses" over the entire period
  
- to do this looped through the array and add the second element of each item to a total

- finances[i][0] is the first element of each item which is the month

- finances[i][1] is the second element of each item which is the profit/loss which we need to add to the total

- total=0 will be the starting point of the total


![SCREENSHOTS
](https://github.com/Lotusniro/Console-Finanaces/blob/main/screenshots/Screenshot%202023-12-24%20at%2012.45.17.png)

then we calculate the average change in profit/losses over the entire period which is the sum of the profit/losses column divided by the length of the array.

-average change = total change / (number of months-1)

-to find the total change we need to find the difference between the current data and the previous data

-change = currentData - previousData

-total change = sum of all changes

-first store all the changes in an empty array

-then loop through the array and push the first change into the array

-find the total change by looping through the array and adding each change to the total change

-then find the average change by dividing the total change by the length of the array

![SCREENSHOTS
](https://github.com/Lotusniro/Console-Finanaces/blob/main/screenshots/Screenshot%202023-12-24%20at%2012.45.31.png)


then I calculated the greatest increase in profits over the entire period which is the maximum value of the profit/losses.
then I calculated the greatest decrease in losses over the entire period which is the minimum value of the profit/losses.

![SCREENSHOTS
](https://github.com/Lotusniro/Console-Finanaces/blob/main/screenshots/Screenshot%202023-12-24%20at%2012.46.00.png)

## Usage
To use this application, the user can simply clone the repository. 

## badges
N/A

## License
This project is licensed under the MIT license.

## Questions
If you have any questions about the repo, open an issue or contact me directly at [
lotusniro in GitHub]


## Link to Deployed Application
