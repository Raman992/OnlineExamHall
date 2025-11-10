# 🧠 Online Exam Hall Management System

The **Online Exam Hall Management System** is a PHP and MySQL-based web application that helps educational institutions
efficiently manage exam hall allocations. It allows administrators to handle student data, exam schedules, room assignments, 
and user accounts all from a simple web interface.

---

##ScreenShots


<img width="885" height="624" alt="image" src="https://github.com/user-attachments/assets/7b5ac478-3f30-4452-9d5e-4bd72c953e6f" />
<img width="800" height="572" alt="image" src="https://github.com/user-attachments/assets/5de5bd8a-41b5-466b-aef1-d03d76fe4462" />

---

## 📁 Project Structure

```
OnlineExamHallManagement/
│
├── admin/                # Admin panel (manages students, rooms, schedules, users)
│   ├── dashboard.php
│   ├── students.php
│   ├── rooms.php
│   ├── schedules.php
│   ├── login.php
│   └── ...
│
├── app/                  # Main application pages
│   ├── about.php
│   ├── contact.php
│   ├── change_password.php
│   ├── connection.php
│   └── ...
│
├── db.sql                # Database structure and sample data
└── readme.md             # Documentation file
```

---

## 🚀 Features

- ✅ Admin authentication system  
- ✅ Manage students, users, rooms, and schedules  
- ✅ Generate and view hall allocations  
- ✅ Manage news and announcements  
- ✅ Contact form for users  
- ✅ MySQL database integration  
- ✅ Simple and clean UI  

---

## ⚙️ Installation Guide

### 🧩 Requirements
- PHP ≥ 7.4  
- MySQL ≥ 5.7  
- Apache server (XAMPP, WAMP, or similar)

### 🔧 Setup Instructions
1. **Download or clone this repository**
   ```bash
   git clone https://github.com/Raman992/OnlineExamHall.git
   ```

2. **Move the project folder** to your web server directory:
   ```
   C:/xampp/htdocs/OnlineExamHallManagement
   ```

3. **Import the database**
   - Open **phpMyAdmin**
   - Create a new database named `online_exam_hall`
   - Import the file `db.sql` located in the project root directory

4. **Update database credentials**
   Open `app/connection.php` and configure:
   ```php
   $host = "localhost";
   $user = "root";
   $pass = "";
   $db   = "online_exam_hall";
   ```

5. **Run the project**
   Open your browser and visit:
   ```
   http://localhost/OnlineExamHallManagement/
   ```

---

## 👨‍💼 Default Admin Credentials

| Username | Password |
|-----------|-----------|
| admin     | admin123  |

> You can change this in the `users` table of the database.

---

## 🧾 Modules Overview

### 👩‍🏫 Admin Panel
- Dashboard overview  
- Manage students  
- Manage exam halls and schedules  
- Publish news and notices  
- View contact messages  

### 🎓 User Side
- View profile  
- Contact support  
- Change password  
- View assigned exam hall  

---

## 🛠️ Technologies Used

| Stack | Technologies |
|--------|--------------|
| Frontend | HTML, CSS, Bootstrap |
| Backend | PHP (Procedural) |
| Database | MySQL |
| Server | Apache |

---

## 💡 Future Enhancements

- Student self-registration  
- Role-based access (Admin / Invigilator / Student)  
- Automatic seat allocation  
- Modern UI using Laravel or React  

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to fork this repository and submit pull requests.

---


## 🧩 Author

Developed by **[Raman Shakya]**  
📧 ramanshakya9863@gmail.com*  
🌐 [https://github.com/Raman992](https://github.com/Raman992)
