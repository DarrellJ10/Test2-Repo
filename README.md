Overview
This project implements a simple Customor Order Management System in Java. It provides functionality for:
- Placing customer orders and calculating the total cost.
- Managing inventory, including stock updates and low stock alerts.
- Handling order statuses (e.g., "Paid", "Ready").
- Running comprehensive tests using JUnit to validate the system's functionality.

Features
1. Order Management:
   - Add items to an order and calculate the total cost.
   - Update the status of an order (e.g., "Pending", "Paid", "Ready").

2. Inventory Management:
   - Add and track items in inventory.
   - Automatically reduce stock after an order is placed.
   - Trigger low stock alerts when inventory falls below a predefined threshold.

3. JUnit Testing:
   - Includes unit tests for key features:
     - Placing orders.
     - Paying for orders.
     - Updating inventory.
     - Checking for low stock alerts.
     - Verifying order status updates.
