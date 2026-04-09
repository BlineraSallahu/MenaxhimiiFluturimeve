This project is a Flight Management System built using PostgreSQL as part of a group database project. It simulates the core operations of an airline system, including managing flights, passengers, bookings, and airports.
The goal of this project is to demonstrate database design, relational modeling, and advanced SQL querying.
Team members: Blinera Sallahu, Xhemile Zymberi, Rina Miftari
Features:
Manage airports and their locations
Store and track flights (departure, arrival, schedules)
Handle passenger information
Create and manage bookings/reservations
Assign seats to passengers
Track aircrafts and their capacities
Perform advanced queries (joins, aggregations, views)
 Database Schema
Main entities in the system:
Airplane
Airport
Baggage
Class
Flights
Passengers
Payment
Staff
Tickets
Relationships
A flight departs from and arrives at airports
A passenger can have multiple bookings
A booking is linked to a specific flight
Airplane is assigned to flights
Technologies Used
PostgreSQL
SQL (DDL, DML, DQL)
pgAdmin / psql (for database management)
