# CP-078: GasGo — LPG Refill Booking and Delivery Management System

A menu-driven console application built in **Python** for managing LPG consumer registrations, enforcing minimum refill intervals, tracking agency cylinder inventory, and flagging delayed deliveries.

## Core Features
1. **Register Consumers:** Registers consumers with unique IDs, delivery areas, and connection types (`Single` or `Double` cylinder).
2. **Minimum Gap Enforcement:** Validates refill requests against the consumer's last delivery day (`15 days` minimum gap for Single Cylinder, `7 days` for Double Cylinder).
3. **Track Delivery Status:** Tracks bookings from `Pending` to `Delivered` and updates the consumer's last delivery record.
4. **Agency Stock Management:** Deducts filled cylinder stock upon booking and allows agency restocking.
5. **Delayed Booking Alerts:** Lists all `Pending` bookings older than **3 days**.

## Stretch Features
- **Subsidy Calculation:** Applies consumer subsidy flags and computes net payable amounts (`Rs. 900` base, `Rs. 200` subsidy discount).
- **Area-Wise Delivery Planning:** Filters pending bookings by locality and calculates total cylinders to load.
- **CSV Export:** Exports booking logs to `gasgo_bookings.csv`.

## output

<img width="558" height="721" alt="Screenshot 2026-11-17 at 2 17 15 PM" src="https://github.com/user-attachments/assets/83bb751f-f2ba-430c-9203-85643ac4f32b" />


## How to Run
```bash
python3 gasgo.py



