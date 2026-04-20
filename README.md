# 24BCY70087-EXPERIMENT-4
# Full Stack Experiments (4.1, 4.2, 4.3)

## Aim

To develop backend systems using Node.js, Express.js, and Redis, demonstrating CLI applications, REST APIs, and concurrency handling.

---

## 📌 Experiments Included

### 🔹 Experiment 4.1 – CLI Employee Management System

* Command-line application using Node.js
* Performs CRUD operations on employee data
* Stores data in JSON file for persistence
* Uses readline module for user interaction

**Key Features:**

* Add employee
* View employees
* Update employee
* Delete employee
* Input validation

---

### 🔹 Experiment 4.2 – REST API for Playing Card Collection

* Backend API using Express.js
* Handles playing card data (suit, value)
* Tested using Postman or browser

**Key Features:**

* GET all cards
* GET card by ID
* POST new card
* PUT update card
* DELETE card

---

### 🔹 Experiment 4.3 – Concurrent Ticket Booking System

* API for booking seats with concurrency control
* Uses Redis for seat locking mechanism
* Prevents double booking

**Key Features:**

* Book seats
* Prevent multiple users booking same seat
* Locking using Redis
* View seat availability

---

## 🛠️ Technologies Used

* Node.js
* Express.js
* Redis
* JavaScript
* Postman

---

## ⚙️ How to Run

### ▶️ Experiment 4.1 (CLI)

1. Open terminal
2. Run:

   ```
   node app.js
   ```

---

### ▶️ Experiment 4.2 (REST API)

1. Install dependencies:

   ```
   npm install express
   ```
2. Run:

   ```
   node server.js
   ```
3. Test API using Postman or browser

---

### ▶️ Experiment 4.3 (Redis Booking)

1. Start Redis server:

   ```
   redis-server
   ```
2. Install dependencies:

   ```
   npm install express redis
   ```
3. Run:

   ```
   node server.js
   ```
4. Test using Postman or UI

---

## 🌐 Optional UI Testing

* HTML files can be used to test APIs in browser
* Connects frontend with backend endpoints

---

## 🎯 Learning Outcomes

* Understanding CLI application development
* Implementing CRUD operations
* Building REST APIs using Express
* Handling concurrency using Redis
* Backend system design fundamentals

---

## 📌 Conclusion

These experiments demonstrate key backend development concepts including data handling, API creation, and concurrency control. Together, they form a strong foundation for full-stack development.

---
