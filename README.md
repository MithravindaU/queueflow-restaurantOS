# 🍽️ QueueFlow Restaurant Order Management System

![Language](https://img.shields.io/badge/Language-C-blue?style=for-the-badge)
![Concepts](https://img.shields.io/badge/Concepts-Data%20Structures-orange?style=for-the-badge)

## 📌 Overview

**QueueFlow** is a menu-driven restaurant order management system developed in C. It demonstrates how fundamental data structures can organize and process restaurant orders efficiently.

The system uses a **circular queue** to manage pending orders in First In, First Out (FIFO) order and a **stack** to store completed orders in Last In, First Out (LIFO) order. Users can place orders, view pending orders, process the next order, view completed orders, and retrieve the most recently completed order.

## ✨ Features

- **Place Orders:** Add food orders with automatically generated order IDs.
- **View Pending Orders:** Display all orders waiting to be processed.
- **Process Orders:** Process pending orders in the order they were placed.
- **View Completed Orders:** Display completed orders, with the latest completion shown first.
- **Retrieve the Last Completed Order:** Pop and retrieve the most recently completed order.
- **Circular Queue:** Reuses available array positions to manage pending orders.
- **Stack-Based History:** Demonstrates LIFO order retrieval.
- **Menu-Driven Interface:** Interact with the system through a simple console menu.

## 🧠 Data Structures Used

| Data structure | Purpose |
|---|---|
| Circular Queue | Stores pending orders and processes them in FIFO order. |
| Stack | Stores completed orders and retrieves the latest one in LIFO order. |
| Structure (`struct`) | Groups each order's ID and food item. |
| Arrays | Store queue and stack entries with a maximum capacity of 100 each. |

## ⚙️ How It Works

1. The user enters a food item to place an order.
2. The system assigns an order ID and adds the order to the pending queue.
3. When the user processes the next order, it is removed from the front of the queue.
4. The processed order is pushed onto the completed-orders stack.
5. The user can view completed orders or retrieve the most recently completed order.

## 🛠️ Technologies Used

- C Programming Language
- Standard C libraries: `stdio.h`, `stdlib.h`, and `string.h`
- Fundamental data structures: circular queue and stack

## ▶️ How to Run

### Compile

Using GCC:

```bash
gcc queueflow.c -o queueflow
```

### Execute

On Windows:

```bash
queueflow.exe
```

On Linux or macOS:

```bash
./queueflow
```

Replace `queueflow.c` with the actual name of your C source file if it differs.

## 🔮 Future Improvements

- Kitchen dashboard for tracking order preparation
- Billing and receipt generation
- Inventory and ingredient management
- Order status tracking
- Input validation and improved error handling
- Persistent storage so orders remain available after the program exits

## 🎯 Learning Outcomes

This project demonstrates practical applications of circular queues and stacks, including FIFO processing, LIFO retrieval, array-based data management, structures, and menu-driven programming in C.

## 👩‍💻 Author

**Mithravinda U**

