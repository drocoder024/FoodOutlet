
# Design Problems 

# FoodOutlet

Problem Statement : 

Requirements: 
1. Customer can pick items from foodenu check for its availability
2. There's a walk-in and online order 
3. Notify customer regarding order status 
4. Identify Different stakeholders involve in the system
5. Admin can add discounts to the order : add on functionality 

Write a code to meet above requirements and show all the lifecycle involving order 
Placement to handing it over to the customer . Use spring repository, controller and other features to write API involved in the code.

# Design Meeting Room Booking 

Problem Statement : 

Requirements: 

Design API contract and DB schema for meeting room booking reservation .
Such that both manager and employee can book seat . 

1. Can be booked for any company 
2. Manager can book for team 
3. Employee can also book for himself 

* challenges 
1. Handle for multiple client and multiple context (Manager /Employee)
2. What if manager has already booked and an Employee comes to book again 
3. What if Manager is trying to book for a team where one of the Employee has already Booked
4. How to handle when multiple Employees come to book seat?

# Design OTP Generator and Validator Service 

Problem Statement : 

Requirements: 

1. Can have multiple clients
2. can be of different length to serve different purpose - delivery verification / account retrieval etc
