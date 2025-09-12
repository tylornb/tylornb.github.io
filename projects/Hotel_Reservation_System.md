---
layout: project
type: project
image: img/hotel_project_thumbnail.jpg
title: "Hotel Reservation System"
# All dates must be YYYY-MM-DD format!
date: 2025-09-11
published: true
labels:
  - Java
  - Coursework
  - 2D Arrays
  - Exception Handling
summary: "A Java program simulating a hotel system using arrays and custom exceptions."
---


## Project Overview
As a part of my ICS 211 coursework under Professor Blanca Polo in Summer 2025, I created a Hotel Reservation System in Java. This project simulated a hotel using a two-dimensional array of `Room` objects to represent the management of the rooms. Each room had an assigned type, either Handicap, Single, Double, Triple, or Deluxe, along with a nightly rate and occupancy status. The project allowed guests to book and vacate rooms, display occupied and vacant rooms, and keep a transaction log that is saved to a file.

## Responsibilities
My role was to take the scaffolding that Professor Polo provided us (namely the `HotelI.java` interface and `HotelDriver.java`) and implement the system's logic. I built the `Room` class with custom exceptions, the `Hotel` class with booking, vacating, and printing methods, and wrote the transaction recording system. I ensured that invalid input, such as a wrong room number or name, was reported. For user interaction, I used menu options that displayed available and occupied rooms organized by floor. 

<img src="/img/hotel_project_flow.png" alt="Hotel Reservation System Flow" width="450"/>

## Lessons Learned
From this project, I gained practical experience with things such as 2D arrays, custom exceptions, and input validation. This project also reinforced the importance of writing programs in a clear structure. A habit that this project enforced was writing detailed comments and method headers to keep everything understandable. These practices helped immensely when I advanced to the later BookList Application, where things like recursion and GUIs require even more careful documentation. Overall, the Hotel Project provided a good foundation in structured programming that allowed me to successfully program more advanced applications.


## Source Code

The full source code is available on [GitHub](https://github.com/tylornb/hotel-booking-system).


*Note: I used ChatGPT to help organize my drafts and suggest edits.*
