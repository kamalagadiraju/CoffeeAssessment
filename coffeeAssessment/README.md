# Developer Assessment

##Description
The assessment comes with 3 JSON files. The files contain data for products, orders and payments.

Write a program that retrieves the following information given the provided files:
- Amount paid per user.
- Amount that each users still owes.

##Requirements
- The program should be written in Java.
- Write production-ready code.
- Document how to run the application.
- Publish the source code into GitHub (using your own personal account) and share it with us.

##How to run this application
- Download the executable jar coffeeAssessment.jar in the github repository. 
- Open command prompt and go to the folder where the downloaded executable jar exists and run the command : java -jar coffeeAssessment.jar
- Output will be displayed in the command prompt.

##Source Code 
- You can find the source code under the coffeeAssessment directory.

##Brief Description Of My Solution
- Iterate through the orders and group them by user.
- Calculate the cost for each order by getting the cost of the drink from products.
- Calculate the total cost of all orders for each user.
- Compare the total amount with the amount already payed by the user with the data from payments.
- Calculate the difference between the total amount to be paid and amount already paid to get the amount owed by user.

##My Observation
- I found that many users in payments.json have already paid more amount than the total cost of their orders.
- I am printing another column "Excess Amount Paid" as many users don't owe any money but have paid more.
- I am not sure if this is a data problem or expected behaviour.
