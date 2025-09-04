Library Management System (Spring Boot + JPA + MySQL)

A simple Library REST API built with Spring Boot, Spring Data JPA (Hibernate), and MySQL.
This project demonstrates how to manage users and books with CRUD operations and borrowing/returning functionality.
**Features**                                              
-Create a new user            

-Fetch all users

-Add a new book

-Fetch all books

-Fetch a specific book

-Update book details

-Delete a book

-Borrow a book

-Return a book

**Tech Stack**

-Java 17

-Spring Boot 3

-Spring Web (REST APIs)

-Spring Data JPA (Hibernate)

-MySQL

-Lombok

-Maven

API Endpoints
1.User APIs

POST /api/users → Create a new user
<img width="1129" height="630" alt="Screenshot 2025-09-04 141832 - Copy (2)" src="https://github.com/user-attachments/assets/b6775322-c0de-4578-8cb7-40646c5e9013" />

GET /api/users → Fetch all users
<img width="1298" height="760" alt="Screenshot 2025-09-04 141850" src="https://github.com/user-attachments/assets/12a1e27b-3e11-47a2-b5fe-dee77ad35883" />

2.Book APIs

POST /api/books → Add a new book
<img width="1312" height="758" alt="Screenshot 2025-09-04 141903" src="https://github.com/user-attachments/assets/d3e1a024-ed39-4fa8-b3cc-987046c0783a" />

GET /api/books → Fetch all books
<img width="1309" height="766" alt="Screenshot 2025-09-04 141917" src="https://github.com/user-attachments/assets/5cbc3009-f381-47d9-8925-c1a4cf12930c" />

GET /api/books/{id} → Fetch specific book
<img width="1169" height="677" alt="Screenshot 2025-09-04 142436" src="https://github.com/user-attachments/assets/13bdaa6f-136b-4ba1-a74a-1c01f8768ed5" />

PUT /api/books/{id} → Update book details
<img width="1489" height="710" alt="Screenshot 2025-09-04 141928" src="https://github.com/user-attachments/assets/eefa8f1b-58ad-4044-8d16-0a51f1e48570" />

DELETE /api/books/{id} → Delete a book
<img width="1489" height="710" alt="Screenshot 2025-09-04 141928" src="https://github.com/user-attachments/assets/1983f5cf-e725-419f-88bb-dcde22c80832" />

3.Borrow/Return APIs
POST /api/books/{bookId}/borrow/{userId} → Borrow a book
<img width="1250" height="587" alt="Screenshot 2025-09-04 142627" src="https://github.com/user-attachments/assets/2dc9ceca-9df1-43d5-989a-946facc81e14" />
POST /api/books/{bookId}/return → Return a book
<img width="1149" height="608" alt="Screenshot 2025-09-04 142701" src="https://github.com/user-attachments/assets/90000153-5337-4607-9f0a-55862899569f" />
