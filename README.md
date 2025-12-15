# Python Ticketing System

## Overview
This project is a Python-based ticketing system designed to simulate real-world ticket booking and seat management operations.

It demonstrates the use of core data structures and system logic commonly used in backend applications.

---

## Key Features
- Seat booking using a 2D seating matrix
- Ticket cancellation with automatic waitlist handling
- Ticket modification functionality
- Priority-based waitlist management
- Fast ticket lookup using a hash table
- Dynamic seating expansion

---

## Data Structures Used
- **2D Lists**: Represent seating layout
- **Dictionary (Hash Table)**: Store and retrieve ticket information efficiently
- **List with Sorting**: Simulate priority queue behavior for waitlist management

---

## How the System Works
1. Seats are represented as a 20×25 grid (500 seats).
2. If a seat is available, it is booked and assigned a unique ticket ID.
3. If a seat is unavailable, the user is added to a priority-based waitlist.
4. When a ticket is canceled, the highest-priority user from the waitlist is automatically assigned the seat.
5. Seating capacity can be dynamically expanded.
6. Tickets can be quickly retrieved using their ticket ID.

---

## Sample Operations
- `book_ticket(name, row, column, priority)`
- `cancel_ticket(ticket_id)`
- `modify_ticket(ticket_id, new_row, new_column)`
- `lookup_ticket(ticket_id)`
- `expand_seating()`

---

## Technologies Used
- Python
- Core Data Structures and Algorithms

---

## Future Improvements
- Add user input handling
- Implement a graphical user interface (GUI)
- Store ticket data in a database
- Improve validation and error handling

