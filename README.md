# what-to-eat

## About

**what-to-eat** is a small personal web application for my household.  
It is designed to collect and share meal ideas, making everyday food decisions easier.

This project is a learning project and is intentionally developed step by step.

---

## Tech Stack

### Frontend
- React
- Vite
- JavaScript
- HTML
- CSS

### Backend (planned)
- Node.js
- Express
- MongoDB

---

## Project Structure

what-to-eat/
  frontend/
  backend/
  README.md


The `backend` folder is intentionally empty and reserved for a future implementation.

---

## Frontend Architecture

The frontend uses **conditional rendering** to control which views are displayed.

- Login related views are rendered only when the user is not authenticated
- Application views are rendered only after authentication

Visual hiding techniques such as `display: none` are not used for access control, as they do not prevent components from being rendered.

---

## Authentication Notes

This project intentionally does not rely on `localStorage` for authentication.

Authentication is treated as a backend responsibility and will be implemented in a later phase.  
The frontend is structured to support a real authentication flow in the future.

---

## Project Status

🚧 **Work in Progress**

The project is currently under development.  
At this stage, only the frontend is being built.  
The backend will be added later as part of further full stack learning.

