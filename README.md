# Airline-Ticket-Booking-System-in-C-language
project: Airline Ticket Booking System in C language using Operating System (concepts)
The Airline Ticket Booking System is a console-based project developed in the C programming language as part of our Operating System course. This project simulates the process of booking airline tickets and incorporates essential OS concepts such as multithreading, mutex locks, and semaphores. The system allows users to perform several operations, including adding new flight tickets, viewing all available tickets, finding a specific ticket by its code, booking tickets, deleting tickets, and viewing old booking records. Multithreading is implemented using pthread.h to allow concurrent booking operations, and synchronization is achieved using pthread_mutex_t and semaphore.h to ensure safe access to shared resources like seat availability. File handling is used to store and retrieve ticket and booking information, ensuring data persistence. The use of threads and synchronization primitives demonstrates how operating systems manage concurrent processes and shared data in real-time systems. This project provides a practical application of OS concepts in a simplified airline reservation environment.

Language Used: 
C Language
Source code run on:
Ubuntu (Command Line)

Write commands to open c file:
- nano project.c
To run this file: 
- gcc –o project project.c
- ./project




