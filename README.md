
# 🏨 Hotel Management System (Java OOP Project)

A **Hotel Management System** built using Java and core Object-Oriented Programming principles. This console-based application helps manage hotel operations such as room bookings, customer details, check-in/check-out processes, and billing.

---

## 📌 Features

* Add new customers and their booking information
* Room availability check
* Room booking and cancellation
* Check-in and check-out functionality
* Automatic bill generation
* Admin panel for room management
* Menu-driven console interface

---

## 🧠 OOP Concepts Used

| Concept            | Application                                                        |
| ------------------ | ------------------------------------------------------------------ |
| **Class & Object** | `Hotel`, `Room`, `Customer`, `BookingManager` etc.                 |
| **Encapsulation**  | Getters and setters to protect data integrity                      |
| **Inheritance**    | `Room` as base class, `DeluxeRoom`, `SuiteRoom` etc. as subclasses |
| **Polymorphism**   | Method overriding for room pricing and billing                     |
| **Abstraction**    | Interfaces for service behaviors like `Billable`                   |

---

## 🛠️ Tech Stack

* **Language**: Java (JDK 8+)
* **IDE**: IntelliJ IDEA / Eclipse / VS Code
* **Database**: None (uses in-memory data structures like `ArrayList`, `HashMap`)



## 📂 Project Structure

```
HotelManagementSystem/
│
├── Main.java
├── Hotel.java
├── Room.java
├── Customer.java
├── BookingManager.java
├── Billable.java
├── RoomType/
│   ├── DeluxeRoom.java
│   ├── SuiteRoom.java
└── utils/
    └── InputHelper.java
```

---

## 👤 Roles

* **Admin**: Add/Edit/Delete rooms, view all bookings
* **Customer**: Book room, check-in/out, view bill

---

## 📷 Sample Screenshots
![Screenshot (90)](https://github.com/user-attachments/assets/4ab4c067-5187-4fed-a614-23804ef6a290)




