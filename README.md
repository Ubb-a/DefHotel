# 🏨 Hotel Booking System (Qt C++)

A modern **desktop application** for managing hotel bookings, developed using **C++ and Qt**.  
It features two main roles: **Employee** and **Guest**, with full integration to a **Microsoft Access** database using **ODBC**.

---

## ✨ Features

### 👨‍💼 Employee Interface
- View pending bookings from the database.
- Approve or reject booking requests.
- Connects to the `PendingBookings` table in the Access DB.

### 🙋‍♂️ Guest Interface
- Submit booking requests.
- Track booking status.
- Rate service after checkout.

### 🗂️ Database Integration
- Uses `.accdb` (Access) database file.
- SQL queries performed through ODBC connection.

### 🎨 Modern UI with Qt
- UI built using Qt Designer (`.ui` files).
- Separated windows for each function (`EmployeeWindow`, `GuestWindow`, etc.).

---

## 🛠️ Tech Stack

- **C++17**
- **Qt 6** (Widgets, SQL)
- **Microsoft Access** via **ODBC**
- **CMake** build system
- **MinGW** on Windows

---

## 🚀 Getting Started

```bash
git clone https://github.com/Ubb-a/DefHotel.git
cd your-repo-name
mkdir build && cd build
cmake ..
cmake --build .
