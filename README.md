# Travego-SQL-

# Introduction

Let’s assume that you have to keep the record of the passengers and price to travel between two cities by bus, for types (Sitting and Sleeper).

The focus of this project is to learn to write different types SQL statements to insert and retrieve data from a database. For database storage we will use MySQL, information related to MySQL and several commands have already been discussed in weekly notebooks. You can refer to these to gather hints on functionality.

# Housekeeping points

● This is a minimal example and may not follow some standard practices.

● We focus on the main flow, and not much error handling.

# Program Organization

The simple program is structured in various layers

1. To give an insight we have two tables Passenger and Price. Please find the more details in the attached ER diagram.
2. Following is the sample data. Please insert this data in the table Passenger. Do ensure that you have at least these data points available in the tables.

# Problem Statement

In this project you have to do the following activities…

● Create the two tables

● Insert data in these tables

● Retrieve the data from these tables based on the requirements mentioned below

1. (Easy) Creating the schema and required tables using sql script or using MySQL workbench UI

a. Create a schema named Travego.

b. Create the tables mentioned above with the mentioned column names.

c. Insert the data in the newly created tables using sql script or using MySQL UI.

2. (Medium) Perform read operation on the designed table created in the above task using SQL script.

a. How many females and how many male passengers traveled a minimum distance of 600 KMs?

b. Find the minimum ticket price of a Sleeper Bus.

c. Select passenger names whose names start with character 'S'

d. Calculate price charged for each passenger displaying Passenger name, Boarding City, Destination City, Bus_Type, Price in the output

e. What are the passenger name(s) and the ticket price for those who traveled 1000 KMs Sitting in a bus?

f. What will be the Sitting and Sleeper bus charge for Pallavi to travel from Bangalore to Panaji?

g. List the distances from the "Passenger" table which are unique (non-repeated distances) in descending order.

h. Display the passenger name and percentage of distance traveled by that passenger from the total distance traveled by all passengers without using user variables
