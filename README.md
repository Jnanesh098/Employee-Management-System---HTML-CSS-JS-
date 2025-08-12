# Employee Management System - (HTML, CSS, JS)

This is a **single-page frontend** for an Employee Management System.  
All the HTML, CSS, and JavaScript are contained in **one file (`index.html`)** for easy testing and deployment.

------------------------

## Project Structure

employee-management-system/
│── index.html # Contains HTML, CSS, and JS in one file

-----------------------

## Features
- **Add Employees** through a form
- **View Employees** in a table
- **Delete Employees** instantly
- **Live Data Fetching** from backend API
- All code in **one file** for simplicity

-----------------------

## Technologies Used
- **HTML5** – Structure of the page
- **CSS3** – Styling directly inside `<style>` tag
- **JavaScript (ES6)** – Logic and API calls
- **Fetch API** – For sending requests to backend

-----------------------

## How to Run
1. Save `index.html` in any folder.
2. Make sure your backend API (Spring Boot or Node.js) is running.
3. Update the backend API link in the script:
   ```javascript
   const API_URL = "http://localhost:8080/api/employees";
4. Double-click index.html to open in your browser.
5. Start adding, viewing, and deleting employees.

----------------------------

## API Endpoints Used

| Method | Endpoint              | Description         |
| ------ | --------------------- | ------------------- |
| GET    | `/api/employees`      | Get all employees   |
| POST   | `/api/employees`      | Create new employee |
| DELETE | `/api/employees/{id}` | Delete employee     |

---------------------------

## Notes
This is only the frontend; it requires a running backend API.
If you want to test without a backend, replace the fetch() calls with dummy data in JavaScript.
