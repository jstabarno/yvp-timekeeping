# YVP Timekeeping System

**Employee Time Management System**  
Powered by **JAINova Studio**

A lightweight, browser-based timekeeping system for managing employee attendance, work schedules, and user accounts. No installation required — just open the file or host it on GitHub Pages.

---

## Live Demo

**Website:** [https://jstabarno.github.io/yvp-timekeeping/](https://jstabarno.github.io/yvp-timekeeping/)

---

## Features

### For All Users
- Clock In / Clock Out (uses laptop time)
- View personal work schedule
- View personal attendance history
- Upload passport-size profile picture
- Automatic 6-hour maximum paid hours calculation
- 8-hour cooldown after clocking out

### For Managers
- Dashboard with today’s attendance overview
- Employee management (add, edit, delete, bulk upload)
- Work Schedule management with **From Date – To Date**
- Bulk upload & extract work schedules (Excel)
- Attendance reports with Excel export
- User Management (create Manager / Rank & File accounts)
- Reset user passwords
- Delete attendance records

---

## Default Login Credentials

| Role            | Username     | Password      |
|-----------------|--------------|---------------|
| **Manager**     | `admin`      | `admin123`    |
| **Rank & File** | `employee1`  | `employee123` |

---

## How to Use

### 1. Open the System
- Go to the live website, or  
- Download `index.html` / `YVP_Timekeeping_System.html` and open it in Chrome or Edge.

### 2. Create Employees
- Login as **admin**
- Go to **Employees** → Add Employee or **Bulk Upload** (Excel)
- Columns supported:  
  `YVP ID | Last Name | First Name | Middle Name | Position | Birthday | Address | Email Address | Contact Number`

### 3. Create Login Accounts
- On the Employee List, click **Create Login** for individual employees  
- Or click **Create Logins for All** to generate accounts for everyone  
- Default credentials:  
  - Username = YVP ID (lowercase)  
  - Password = YVP ID

### 4. Assign Work Schedules
- Go to **Work Schedule**
- Download the template
- Fill in:  
  `YVP ID | From Date (MM/DD/YYYY) | To Date (MM/DD/YYYY) | Schedule (e.g. 9PM - 6AM)`
- Upload the file
- You can also **Extract** all schedules to Excel

### 5. Clock In / Clock Out
- Employees login and use the **CLOCK IN** / **CLOCK OUT** buttons on the Dashboard
- Total hours are automatically calculated (max 6 hours)

---

## Tech Stack

- Pure HTML + CSS + JavaScript
- Data stored in browser `localStorage`
- Excel import/export via [SheetJS](https://sheetjs.com/)

---

## Notes

- All data is stored locally in the browser (localStorage).
- Clearing browser data will reset the system.
- Best used in Google Chrome or Microsoft Edge.

---

## License

This project is created for **YVP Administrative Support Services**.  
Powered by **JAINova Studio**.
