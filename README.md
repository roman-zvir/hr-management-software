# HR Management Software

A comprehensive C++ application designed for managing employee data using Object-Oriented Programming principles. The software includes modules for both administrators and users, ensuring efficient data handling, exceptional situation management, and user feedback.

---

## Features

### Exceptional Situation Handling
- Invalid input formats (e.g., characters in numeric fields).
- Incorrect input values (e.g., negative prices).
- Missing data files.
- No results found for search queries.
- Invalid record deletion attempts (e.g., record index out of range).
- Duplicate account logins.
- Navigation capabilities for going back.
- Confirmation for irreversible actions (e.g., file/record deletion).
- Feedback messages for successful operations (e.g., file creation, record deletion).

### Employee Data Management
- **Employee Information:**
  - Full name.
  - Date of birth.
  - Department name.
  - Position.
  - Start date of employment.
- **Individual Task:**
  - Display employees of retirement age in descending order of seniority.

---

## Program Modules

### Administrator Module
The administrator module provides tools for managing user accounts, files, and data.

#### Submodules and Functionalities:

1. **User Accounts Management:**
   - View all accounts.
   - Add new accounts.
   - Edit existing accounts.
   - Delete accounts.

2. **File Operations:**
   - Read data from a file.
   - Write data to a file.
   - Append data to an existing file.
   - Delete files.

3. **Data Management:**
   - **Edit Mode:**
     - View all data.
     - Add new records.
     - Delete records.
     - Edit records.
   - **Processing Mode:**
     - Perform the individual task.
     - Search data (at least three parameters).
     - Sort data (at least three parameters).

![Administrator Menu](https://github.com/Taras-P-Kob/programs-for-recording-the-seniority-of-the-company-s-employees/assets/119957094/73c0dec7-7dea-445c-99a9-115a59438775)

### User Module
The user module allows basic operations on employee data for users with restricted access.

#### Functionalities:
- View all data.
- Perform the individual task.
- Search data (at least three parameters).
- Sort data (at least three parameters).

![User Menu](https://github.com/Taras-P-Kob/programs-for-recording-the-seniority-of-the-company-s-employees/assets/119957094/dfa10819-82f6-449f-9e77-2b873a5d496f)

---

## Program Workflow

### 1. Authorization
The program verifies user credentials (login and password) from a `data.txt` file.
- **Admin Access:** Grants access to the administrator module.
- **User Access:** Grants access to the user module.

### 2. Administrator Module
The administrator module enables full control over employee and user data.

#### Example Operations:
- Adding a new user account:

![Add User Example](https://github.com/Taras-P-Kob/programs-for-recording-the-seniority-of-the-company-s-employees/assets/119957094/25aa66b7-0bb6-4f88-b695-cba7a040e832)

- Displaying and sorting employee data by various criteria:

![Sorting Example](https://github.com/Taras-P-Kob/programs-for-recording-the-seniority-of-the-company-s-employees/assets/119957094/706c2843-d4eb-4404-9cfa-8c709c4ade51)

### 3. User Module
The user module provides essential functionalities for accessing and analyzing employee data.

#### Example Operations:
- Searching employee data by start date:

![Search Example](https://github.com/Taras-P-Kob/programs-for-recording-the-seniority-of-the-company-s-employees/assets/119957094/85e93ef8-c3b3-460e-99fa-bdbaa24537e0)

---

## Development Highlights
- **Programming Language:** C++
- **Paradigm:** Object-Oriented Programming (OOP)
- **Focus Areas:**
  - Robust error handling.
  - Intuitive navigation.
  - Comprehensive data management.

---

## Getting Started

### Prerequisites
- C++ compiler.
- Standard libraries and development tools.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/roman-zvir/hr-management-software.git
   ```
2. Compile the code:
   ```bash
   g++ -o hr_management main.cpp
   ```
3. Run the program:
   ```bash
   ./hr_management
   ```

---

## Screenshots
1. **Administrator Menu:**

![Administrator Menu](https://github.com/Taras-P-Kob/programs-for-recording-the-seniority-of-the-company-s-employees/assets/119957094/73c0dec7-7dea-445c-99a9-115a59438775)

2. **User Menu:**

![User Menu](https://github.com/Taras-P-Kob/programs-for-recording-the-seniority-of-the-company-s-employees/assets/119957094/dfa10819-82f6-449f-9e77-2b873a5d496f)

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgments
Special thanks to the contributors and the open-source community for their support and inspiration.
