# School Library Management System (Academic Project)

## Description

This repository is a **public showcase** of an **academic PHP web application** developed as part of university coursework.

The project is a **School Library Management System** designed to demonstrate a solid understanding of **backend web development concepts** using native PHP, without relying on large frameworks.  
The focus of the project is on **application architecture**, **request routing**, and **complete user/admin workflows**, rather than production deployment.

The application follows a **front-controller pattern**, where a single entry point (`index.php`) acts as a router and dispatches incoming requests to the appropriate controllers. The codebase is organized using an **MVC-style structure** to clearly separate routing logic, business logic, and presentation.

The **full source code is intentionally kept in a private repository**.  
This public repository exists only to document the project’s **features, architecture, and learning outcomes** for **academic evaluation and portfolio purposes**.

---

## Project Context (Academic)

- Developed as part of a university academic program  
- Group project  
- Focused on learning backend architecture, routing, and workflow design  
- Not intended as a production or commercial system  

---

## Key Features

- Google Authentication (OAuth) for user login
- User profile management (view and update personal information)
- Wishlist functionality
- Advanced search with filters
- Pagination for large book listings
- Book availability tracking
- Book request workflows:
  - borrow a book
  - reserve a book if unavailable
  - request an extension of the borrowing period
- Automatic reservation handling when a book becomes available
- Notification system for request status updates
- Admin approval workflow
- PDF receipt generation when a request is approved
- Activity logging
- Contact system to communicate with administrators

---

## Application Architecture

The application is built around the following concepts:

### Front Controller (Router)
All HTTP requests go through a single entry point (`index.php`), which determines the requested route and dispatches the request to the appropriate controller.

### MVC-style Organization
- **Controllers** handle request logic and workflows  
- **Models** represent application data and rules  
- **Views** render the user interface  

### Role-based Workflows
- Users can search, request, reserve books, manage profiles, and receive notifications
- Administrators can approve requests, manage availability, and respond to users

This architecture was chosen to demonstrate a clear understanding of how structured web applications operate internally.

---

## Why the Source Code Is Private

The complete implementation is maintained in a **private repository** to:

- Protect authentication and configuration logic
- Avoid exposing sensitive implementation details
- Follow academic and security best practices

This public repository serves as a **technical and functional overview**, not as a source code distribution.

---

## Learning Outcomes

Through this project, the following concepts were applied and reinforced:

- PHP backend development without frameworks
- HTTP request routing and controllers
- Application flow and state management
- User and admin interaction workflows
- Notifications and asynchronous logic
- File generation (PDF receipts)
- Secure handling of authentication concepts
- Clean project organization and documentation

---

## Screenshots & Demo

Screenshots and demonstrations can be added to illustrate:

- Google login
- Search and filtering
- Book listings with pagination
- Request and reservation flows
- Notifications
- PDF receipt generation

---

## Author

back-end Developed by **El fahime Mohamed Zayd** 
designed by **Aoutmani Mohamed amine**
Academic project for software engineering and web development studies.
