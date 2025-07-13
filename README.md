# 📚 Library Management System – Java RESTful API

This project is part of a code assessment for **Biz Digital IT Services Pvt. Ltd.**  
It is a simple Java-based RESTful API designed to manage a library's book catalog.

---

## 🎯 Objective

To demonstrate understanding of:
- Java (8+)
- Object-Oriented Programming
- RESTful API Design
- Spring Boot (Optional)
- In-memory data storage and manipulation

---

## 🛠️ Features

- ➕ Add a new book
- 📚 Retrieve all books
- 🔍 Get book details by ID
- ❌ Delete a book
- ♻️ Update book availability

---

## 📑 Book Entity

Each book has the following attributes:

| Field     | Type     | Description            |
|-----------|----------|------------------------|
| `id`      | Integer  | Unique identifier      |
| `title`   | String   | Title of the book      |
| `author`  | String   | Author's name          |
| `isbn`    | String   | ISBN number            |
| `available` | Boolean | Availability status    |

---

## 💻 Technologies Used

- Java 8+
- Spring Boot (Optional)
- RESTful API design
- In-Memory Data Storage (List)

---

## 🚀 How to Run

### 1️⃣ Clone the repository:
```bash
git clone https://github.com/Pramod-Patil123/library1.git
cd library1


2️⃣ Run using Spring Boot
If it's a Spring Boot app, use:

bash
Copy code
./mvnw spring-boot:run
or open in IntelliJ IDEA/VS Code and run LibraryApplication.java.

📬 Sample Requests (If REST API used)
➕ Add Book:
POST /books

json
Copy code
{
  "id": 1,
  "title": "Effective Java",
  "author": "Joshua Bloch",
  "isbn": "9780134685991",
  "available": true
}
📚 Get All Books:
GET /books

🔍 Get Book by ID:
GET /books/1

❌ Delete Book:
DELETE /books/1

♻️ Update Availability:
PATCH /books/1/availability?status=false

✅ Bonus
✅ Code is encapsulated using Service, Controller, and Repository layers.

✅ Validations applied (e.g., title should not be empty).

✅ Optional: Postman Collection link can be added.

🔗 GitHub Repository
📂 View Project on GitHub

👨‍💻 Author
Pramod Ratilal Patil
📧 pramodrp0202@gmail.com
📱 +91 9130667095

🏢 Company
Biz Digital IT Services Pvt. Ltd.
Reputable AWS & Zoho partner delivering innovative IT solutions.

