# 🚌 SmartBus – Python Ticket Booking System

## 📌 Project Overview

SmartBus is a console-based Python application that simulates a bus ticket booking system.

The system allows users to view buses, select a bus, choose seats, enter passenger details, calculate fares, select a payment method, generate an e-ticket, and cancel bookings.

## ✨ Features

- 🚌 View available buses
- 🎫 Bus selection
- 💺 Seat management
- 👤 Passenger details
- 💰 Fare calculation
- 💳 Payment method selection
- 🎟️ E-ticket generation
- ❌ Ticket cancellation

## 🐍 Python Concepts Used

- Variables
- Input and Output
- Conditional Statements
- `for` and `while` loops
- Lists
- Dictionaries
- User-defined functions
- Function parameters and return values
- `try-except` exception handling
- Input validation
- String methods

## ⭐ Important Python Concepts

### User-Defined Functions

The project is divided into separate functions such as:

- `main_menu()`
- `bus_information()`
- `bus_selection()`
- `seat_management()`
- `passenger_details()`
- `booking()`
- `fare_calculation()`
- `payment()`
- `ticket_display()`
- `cancellation()`

### Dictionaries

Dictionaries are used to store structured bus and booking information using key-value pairs.

### Lists

Lists are used to store seats and booking records.

### Exception Handling

`try-except` is used to handle invalid user input.

### `zfill()` String Method

The `zfill()` method is used to generate formatted booking IDs.

```python
booking_id = "SB" + str(len(bookings) + 1).zfill(3)
