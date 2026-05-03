# PNR-TICKETNG-SYSTEM
Final requirement for the course CC104: Data Structures and Algorithms.

## Overview
PNR Ticketing System is a console-based railway ticketing system developed using the C programming language. It is designed for use by train personnel, such as ticket tellers and onboard staff, to efficiently handle commuter transactions.

## Data Structures & Algorithms

## Data Structure
 
| Data   Structure       | Description                         |
| -----------------------|----------------------------------- |
| **Array**              | Stores all station data including station names, base fares, and trip schedules (southbound and northbound). It allows fast access using index and is used when displaying schedules, validating stations, and calculating fares. |
|   **Linked-List**       |Used in Ticket *ticketHead where each ticket is dynamically created and linked using next. This supports adding tickets, updating or canceling tickets, and traversing all records for display and inspection..        |
|   **Stack**            | Implemented using an array in Stack. Stores operation history in LIFO order, keeping previous ticket states for tracking and undo purposes.       |
|   **Queues**           | Implemented using an array in Queue. Stores ticket operations (e.g., ticket issued) in FIFO order to track and display processing actions.      |


## Algorithm

|   Algorithm         | Description                         |
| --------------     | ----------------------------------- |
|  Linear Search     | Searches station names by comparing user input with all stored station names in the array. Used to validate origin and destination inputs. |
| Bubble Sort |Sorts the linked list of tickets by Ticket ID in ascending order for organized display of ticket history.         |

## Feature


- **Ticket Management System** – Handles full ticket transactions including issue, inspection, cancellation, and history viewing using a linked list structure.
- **Schedule Viewing** – Displays southbound and northbound train schedules using station data, including trip times and fares.
- **Fare & Discount System** – Computes fare based on station difference and applies discounts for Student, PWD, and Senior with ID verification.
- **Payment Processing** – Supports Cash and E-Wallet (GCash/PayMaya), validates payment, computes change, and confirms ticket issuance.
- **Station Validation** – Uses linear search to verify origin and destination stations before ticket creation.
- **Operation Tracking** – Uses Queue (FIFO) to record ticket actions and Stack (LIFO) to store operation history.
- **Data Management** – Stores ticket records using a linked list and ensures persistence through binary file saving and loading (tickets.dat).


## How to Compile and Run

### Requirements
```
Any C compiler (preferably Dev-C++ on Windows or GCC with Windows support)
```

### Run steps
```
- Open Dev-C++
- Select main.c file
- Click Compile & Run or press F11
```

