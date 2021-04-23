# College-OOP-PBL - Railway Reservation System

OOP Subject Project Based Learning 
Github: https://github.com/sidhant-khamankar/Railway-Reservation-System

Topic: Railway Reservation System

Description: This program will allow admin to generate user ids ,set Train info and see all Reservations, users and cancellations. User can Reserve, Enquire and Cancel Ticket. Ticket fare will be calculated based upon concession category. Every data will be written to files in binary form using file Handling. Updation of Seats after reservation and cancellation takes place as well. PNR is generated randomly using random function.

## Flowchart Links

### Main Admin and User: https://app.code2flow.com/cQIVUxM2y1Vo
![main database user](https://github.com/sidhant-khamankar/Railway-Reservation-System/blob/main/flowcharts/main%20database%20user.png)

### Admin User Management: https://app.code2flow.com/dOELf08yoBxq
![database  manage](https://github.com/sidhant-khamankar/Railway-Reservation-System/blob/main/flowcharts/database%20%20manage.png)

### User Reserve and Enquire: https://app.code2flow.com/RAF4yK3bkvCR
![Reservation enquire](https://github.com/sidhant-khamankar/Railway-Reservation-System/blob/main/flowcharts/Reservation%20enquire.png)

### User Cancel: https://app.code2flow.com/argHhQHQ15fH
![User cancel](https://github.com/sidhant-khamankar/Railway-Reservation-System/blob/main/flowcharts/User%20cancel.png)

## Classes:

### Train: 

Contains Train Details like name, number, class type and their fares, date, boarding and destination stations. It has function for inputting these details and printing them.

### Reserve: 

Contains Passenger details like name, age and the corresponding booked train details along with PNR number, concession, reserved seats. It has function for inputting these details and printing them.

### Cancel: 

Similar to Reserve class.

### User:
Contains id and password of user. It has function for inputting these details and printing them.

## Functions

### Admin:

It has subfunctions to Add Train, Display all trains and following functions

#### User Management: 

It can be used to add new Users and display existing users with their ID and password.

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

## Output

Admin Adds Trains

![admin add trains](https://user-images.githubusercontent.com/63101268/99869289-cbb8dc00-2bef-11eb-9715-c09c270a3577.jpg)

Admin display trains

![admin display trains](https://user-images.githubusercontent.com/63101268/99869296-cf4c6300-2bef-11eb-92bf-c4073e1c58ed.jpg)

Admin adds and displays users

![admin user add and display](https://user-images.githubusercontent.com/63101268/99869297-cfe4f980-2bef-11eb-8e30-4a3fc541b072.jpg)

User Reserves

![user reserv_1](https://user-images.githubusercontent.com/63101268/99869301-d1aebd00-2bef-11eb-97c1-9e396ac74d0a.jpg)
![user reserv_2](https://user-images.githubusercontent.com/63101268/99869302-d2475380-2bef-11eb-81ac-091fc6618de4.jpg)

User Enquires after Reservation

![user enquiry after reservation](https://user-images.githubusercontent.com/63101268/99869299-d1162680-2bef-11eb-989c-194a80dec75e.jpg)

Admin displays all reservations

![admin display reservations](https://user-images.githubusercontent.com/63101268/99869295-ceb3cc80-2bef-11eb-950f-fd3448fc85fc.jpg)

User cancels reservation

![user cancel](https://user-images.githubusercontent.com/63101268/99869298-d07d9000-2bef-11eb-8a90-5c15e71f225c.jpg)

Admin displays all cancellations

![admin display cancellations](https://user-images.githubusercontent.com/63101268/99869291-cd829f80-2bef-11eb-90de-ca1d2fb4e60e.jpg)


## Applications
We can use a similar system for bus, airline reservations, theatre ticket booking and Library Management i.e It will be used wherever there is need of booking or reserving. 

## Conclusion
We learnt to implement Object Oriented Programming Concepts like Encapsulation and Abstraction and File Handling Concept in this project.
