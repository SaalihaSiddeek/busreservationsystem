# Bus Seat Reservation System

This Bus Seat Reservation System is designed to streamline bus seat booking and management with a user-friendly interface and efficient back-end operations. The system provides the following functionalities:

## Customer Registration:
Customers can register by providing details such as:
- Name
- Mobile Number
- Email ID
- City
- Age

## Bus Registration:
Admins can register buses with the following details:
- Bus Number
- Total Seats
- Starting Point
- Ending Point
- Starting Time
- Fare

## Bus Search:
Customers can search for available buses based on their travel needs, including starting point, destination, and timing.

## Seat Reservation:
Customers can reserve seats on their chosen buses. Upon successful reservation:
- The customer is notified via a message.
- All reservation details are saved for future reference.

## Reservation Cancellation:
Customers can cancel their reservations at any time. Upon cancellation:
- The customer is notified via a message.
- The next customer in line on the waiting list for that seat is automatically notified of the availability.

## Waiting List Implementation:
If a bus is fully booked, customers can request a seat and will be placed on a waiting list. Once a seat becomes available, the system automatically notifies the next customer in the queue. The waiting list uses a simple linked list data structure to manage customers in a first-come, first-served manner.
