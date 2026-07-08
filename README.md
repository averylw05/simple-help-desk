# Simple Help Desk

A full-stack help desk ticket system built for a software engineering internship portfolio.

## Tech Stack

### Backend
- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database

### Frontend
- HTML
- CSS
- JavaScript
- Fetch API

## Features

- Create support tickets
- View all tickets
- Filter by status
- Update ticket status
- Delete tickets
- Backend REST API
- H2 in-memory database
- Seed sample ticket data

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/tickets` | Get all tickets |
| POST | `/api/tickets` | Create a ticket |
| PUT | `/api/tickets/{id}/status` | Update ticket status |
| DELETE | `/api/tickets/{id}` | Delete ticket |

## How to Run

### 1. Start the Backend

Open a terminal in the `backend` folder.

Run:

```bash
mvn spring-boot:run
```

Backend runs on:

```text
http://localhost:8080
```

Test API:

```text
http://localhost:8080/api/tickets
```

H2 database console:

```text
http://localhost:8080/h2-console
```

H2 settings:

```text
JDBC URL: jdbc:h2:mem:helpdeskdb
Username: sa
Password: leave blank
```

### 2. Start the Frontend

Open `frontend/index.html` in your browser.

Or use VS Code Live Server.

## Portfolio Description

Simple Help Desk is a full-stack ticket management system built with Java, Spring Boot, Spring Data JPA, H2, HTML, CSS, and JavaScript. It allows users to create support tickets, view tickets from a backend API, update ticket statuses, and delete tickets.

## Future Improvements

- Replace H2 with MySQL
- Add login and user roles
- Add ticket priority
- Add comments on tickets
- Add assigned technician field
- Convert frontend to Angular
