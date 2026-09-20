# 🚌 SmartBus – Python Ticket Booking System

## 📌 Project Overview

SmartBus is a console-based Python application that simulates a bus ticket booking system.

The system allows users to view available buses, select a bus, choose seats, enter passenger details, calculate fares, select a payment method, generate an e-ticket, and cancel bookings.

---

## 🎯 Objectives

- To develop a practical Python-based bus ticket booking system.
- To apply fundamental Python programming concepts in a real-world application.
- To implement user input and validation.
- To manage bus, seat, passenger, and booking information.
- To calculate fares and simulate payment.
- To generate a formatted e-ticket.
- To implement ticket cancellation.

---

## ✨ Features

### 🚌 1. Bus Information

Displays available buses with:

- Bus number
- Source
- Destination
- Departure time
- Bus type
- Fare

### 🎫 2. Bus Selection

Allows the user to select a bus from the available buses.

### 💺 3. Seat Management

Allows users to:

- View available seats
- Select seats
- Prevent duplicate seat selection
- Validate the number of seats

### 👤 4. Passenger Details

Collects:

- Passenger name
- Age
- Gender
- Phone number
- Passenger ID
- Source
- Destination

### 💰 5. Fare Calculation

Calculates the total fare based on the basic fare and number of selected seats.

A 10% discount is applied in the current implementation.

### 💳 6. Payment

Provides three payment options:

- UPI
- Card
- Cash

The payment status is simulated as successful after selecting a valid payment method.

### 🎟️ 7. E-Ticket Generation

Generates a formatted e-ticket containing:

- Booking ID
- Passenger details
- Passenger ID
- Selected seats
- Journey details
- Total amount
- Payment method
- Payment status

### ❌ 8. Ticket Cancellation

Allows users to:

- Enter a booking ID
- View booking information
- Cancel the booking
- Calculate cancellation charge
- Calculate refund amount
- Update booking status

---

## 🐍 Python Concepts Used

- Variables
- Input and Output
- Conditional Statements
- `if`, `elif`, and `else`
- `for` and `while` loops
- Lists
- Dictionaries
- User-defined functions
- Function parameters
- Return values
- `try-except` exception handling
- Input validation
- String methods

---

## ⭐ Important Python Concepts Implemented

### 1. User-Defined Functions

The project is divided into multiple functions to make the program organized and easier to maintain.

Functions used include:

```python
main_menu()
bus_information()
bus_selection()
seat_management()
passenger_details()
booking()
fare_calculation()
payment()
ticket_display()
cancellation()
```

### 2. Dictionaries

Dictionaries are used to store structured bus and booking information using key-value pairs.

Example:

```python
buses = {
    1: {
        "number": "SB101",
        "from": "Chennai",
        "to": "Bangalore",
        "time": "09:00 AM",
        "type": "AC Sleeper",
        "fare": 800
    }
}
```

### 3. Lists

Lists are used to store available seats, selected seats, and booking records.

Example:

```python
booked_seat = []
```

### 4. Loops

`for` and `while` loops are used for:

- Displaying buses
- Validating user input
- Selecting seats
- Selecting payment methods
- Repeating operations until valid input is provided

### 5. Exception Handling

`try-except` is used to handle invalid numerical input and prevent the program from terminating unexpectedly.

Example:

```python
try:
    choice = int(input("Enter bus choice: "))
except ValueError:
    print("Please enter a number.")
```

### 6. Input Validation

The project validates user input such as:

- Bus selection
- Number of seats
- Seat names
- Payment method
- Cancellation confirmation

### 7. `zfill()` String Method

The `zfill()` method is used to create formatted booking IDs.

```python
booking_id = "SB" + str(len(bookings) + 1).zfill(3)
```

Example:

```text
SB001
SB002
SB003
```

The `zfill(3)` method adds leading zeros so that the booking number contains three digits.

This gives the booking ID a consistent format.

---

## 🔄 System Workflow

```text
Start
  ↓
Main Menu
  ↓
View Buses / Book Ticket / Cancel Ticket / Exit
  ↓
Select Bus
  ↓
Select Seats
  ↓
Enter Passenger Details
  ↓
Calculate Fare
  ↓
Select Payment Method
  ↓
Generate E-Ticket
  ↓
End
```

---

# 🖥️ Project Screenshots

## 📸 Complete Project Flow

The following image shows all major SmartBus outputs arranged in the correct project flow.

![Complete SmartBus Project Flow](SmartBus_Project_Screenshots_One_by_One.png)

---

## 1. Main Menu

![Main Menu](main-menu.png)

---

## 2. Bus Information

![Bus Information](bus-information.png)

---

## 3. Booking Process

![Booking Process](booking-process.png)

---

## 4. Fare and Payment

![Fare and Payment](fare-payment.png)

---

## 5. E-Ticket

![E-Ticket](e-ticket.png)

---

## 6. Cancellation

![Cancellation](cancellation.png)

---

## 🛠️ Technologies Used

### Programming Language

- **Python**

### Application Type

- Console-based application

### Python Features

- Functions
- Lists
- Dictionaries
- Loops
- Conditional statements
- Exception handling
- String methods

### External Libraries

**None**

The project uses Python's built-in programming features and does not require external libraries.

---

## 📂 Project Structure

```text
SmartBus-Python-Project/
│
├── README.md
├── SmartBus.py
│
├── SmartBus_Project_Screenshots_One_by_One.png
│
├── main-menu.png
├── bus-information.png
├── booking-process.png
├── fare-payment.png
├── e-ticket.png
└── cancellation.png
```

---

## 📌 Limitations

- Booking information is stored only while the program is running.
- Booking data is not stored permanently.
- No database is currently connected.
- Payment is simulated and does not perform real transactions.
- The application is console-based.
- No graphical user interface is implemented.

---

## 🚀 Future Enhancements

- Database integration
- Permanent booking storage
- Graphical User Interface (GUI)
- User login and authentication
- Real-time bus availability
- Online payment integration
- Improved ticket generation
- Persistent passenger and booking records

---

## 📝 Conclusion

The **SmartBus Python Project** demonstrates how fundamental Python programming concepts can be combined to create a practical bus ticket booking system.

The project implements bus selection, seat management, passenger information, fare calculation, payment selection, e-ticket generation, and ticket cancellation.

Through this project, concepts such as **user-defined functions, lists, dictionaries, loops, conditional statements, exception handling, input validation, and the `zfill()` string method** were applied in a practical real-world scenario.

This project helped strengthen Python programming skills by applying theoretical concepts to a functional console-based application.

---

## 👩‍💻 Project Information

**Project Name:** SmartBus – Python Ticket Booking System  
**Programming Language:** Python  
**Project Type:** Academic Python Project  
**Application Type:** Console-Based Application
