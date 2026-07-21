# Flight Reservation System

A command-line flight booking application written in C designed to manage seat selections, passenger age verification, and automated fare calculations for a flight

## Features
- **Class Selection:** Supports both Business Class and Economy Class booking workflows.
- **Seat Validation:** Enforces structural boundaries and restrictions (e.g., specific unavailable seat numbers in Economy).
- **Dynamic Pricing & Age Breakdown:** Calculates individual and total fares based on passenger age classifications and window seat allocations.
- **Bulk Discounts:** Applies conditional promotional deductions for cumulative totals crossing threshold values.

## Project Structure
- `main.c`: Contains the core console logic, menu loops, and pricing algorithms.
- `requirements.txt`: Environment and build tool specifications.

## Compilation & Execution
1. Ensure you have a standard C compiler installed (such as `gcc`).
2. Compile the source file:
   ```bash
   gcc main.c -o flight_system
