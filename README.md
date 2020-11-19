# College-OOP-PBL - Railway Reservation System

OOP Subject Project Based Learning

Topic: Railway Reservation System

Description: This program will allow admin to generate user ids ,set Train info and see all Reservations, users and cancellations. User can Reserve, Enquire and Cancel Ticket. Ticket fare will be calculated based upon concession category. Every data will be written to files in binary form using file Handling. Updation of Seats after reservation and cancellation takes place as well. PNR is generated randomly using random function.

## Flowchart Links

### Main Admin and User: https://app.code2flow.com/cQIVUxM2y1Vo
![main database user](https://user-images.githubusercontent.com/63101268/98447719-1b59cb00-214d-11eb-859a-354affed0585.png)

### Admin User Management: https://app.code2flow.com/dOELf08yoBxq
![database  manage](https://user-images.githubusercontent.com/63101268/98447717-19900780-214d-11eb-9eae-df4fe76b7b18.png)

### User Reserve and Enquire: https://app.code2flow.com/RAF4yK3bkvCR
![Reservation enquire](https://user-images.githubusercontent.com/63101268/98447720-1c8af800-214d-11eb-8f1c-9de2217ecc5e.png)

### User Cancel: https://app.code2flow.com/argHhQHQ15fH
![User cancel](https://user-images.githubusercontent.com/63101268/98447721-1d238e80-214d-11eb-8c2f-3b0515efb720.png)

## Classes:

### Train: 

Contains Train Details like name, number, class type and their fares, date, boarding and destination stations. It has function for inputting these details and printing them.

### Reserve: 

Contains Passenger details like name, age and the corressponding booked train details along with PNR number, concession, reserved seats. It has function for inputting these details and printing them.

### Cancel: 

Similar to Reserve class.

### User:
Contains id and password of user. It has function for inputting these details and printing them.

## Functions

### Admin:

It has subfunctions to Add Train, Display all trains and following functions

#### User Management: 

It can be used to add new Users and display existing users with their ID and passoword.

#### Display Reservations:

It reads records from Reservation file and display them.

#### Display Cancellations:

It reads records from Cancelled file and display them.

### User: 

A particular user can login using his/her credentials. It has following subfunctions

#### Reserve:

It takes ticket details from user as input. Calculates concession and updates seats in Train file and then generates PNR Number using random number generator.

#### Cancel:

It takes PNR number as input and finds the reserved ticket and deletes it from Reservation file and Updates Cancellation file.

#### Enquiry:

Display all Trains Details from Train file.

## Files

### id.txt: 
Binary file. Contains User Records.

### t.txt:
Binary file. Contains Train Records.

### p.txt:
Binary file. Contains Reservation Records.

### cn.txt:
Binary file. Contains Cancellation Records.

### temp.txt:
Binary file. Holds Reservation Records except Cancellation Records.

## Applications
We can use a similar system for bus, airline reservations, theatre ticket booking and Library Management i.e It will be used wherever there is need of booking or reserving. 

## Conclusion
We learnt to implement Object Oriented Programming and File Handling Concept in this project.
