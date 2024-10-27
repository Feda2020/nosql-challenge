# nosql-challenge

## Table of contents

* [Description](#Description)
* [Part 1](#Part-1)
* [Part 2](#Part-2)
* [Part 3](#Part-3)
* [Questions](#Questions)
* [References](#References)

## Description

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. For this assignment the editors of a food magazine, Eat Safe, Love, requested to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Part 1

* Import the data provided in the establishments.json file from the Terminal. 
* Name the database uk_food and the collection establishments. 
* Import the libraries needed: PyMongo and Pretty Print (pprint).
* Create an instance of the Mongo Client.
* Confirm that I created the database and loaded the data properly:

1. List the databases you have in MongoDB. Confirm that uk_food is listed.
2. List the collection(s) in the database to ensure that establishments is there.
3. Find and display one document in the establishments collection using find_one and display with pprint.

* Assign the establishments collection to a variable to prepare the collection for use.

## Part 2
Answer requests for the magazine editors:

* An exciting new halal restaurant just opened in Greenwich, but hasn't been rated yet. The magazine has asked you to include it in your analysis.
* Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields. 
* Update the new restaurant with the BusinessTypeID you found.
* Finding and deleting all establishments in Dover.
* Changing the following from string to decimal numbers:

1. Use update_many to convert latitude and longitude to decimal numbers.
2. Use update_many to convert RatingValue to integer numbers. 

## Part 3

Data analysis to answer the following question:

* Which establishments have a hygiene score equal to 20?
* Which establishments in London have a RatingValue greater than or equal to 4?
* What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
* How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

## Questions

In case of any additional questions please visit my GitHub link: [Feda2020](https://github.com/Feda2020) 

## References
 
 * Xpert Learning Assistant
 * Class Activities.