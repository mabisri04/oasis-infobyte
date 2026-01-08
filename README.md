 Train Ticket Booking Application

This Java-based console application manages complete railway reservation workflows through three independent modules:

User Authentication Module
Handles secure login verification with hardcoded username/password storage in memory.

Ticket Booking Engine
- Collects traveler information  
- Auto-retrieves available train schedules  
- Generates unique 8-character PNR codes for each reservation  

PNR Cancellation Portal
Enables ticket lookup, validation, and confirmed cancellation by entering the booking reference number.

Object-Oriented Design 
Custom `Passenger` and `Booking` classes organize data effectively following OOP principles.

In-Memory Data Management
`ArrayList` maintains booking records while `HashMap` provides fast PNR lookups.

Production-Ready Features
Comprehensive exception handling with try-catch ensures graceful error recovery and validates all user inputs.
