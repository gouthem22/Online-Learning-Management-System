
# Online Learning Management System (OLMS)

An **Online Learning Management System** built using **PHP, MySQL, HTML, CSS, and JavaScript**.  
This project allows admins to manage courses, students, and progress, while students can register, enroll in courses, and track their learning journey.

---

## 🚀 Features
- User authentication (**Admin & Student login**)
- Course management (**Add, Edit, Delete**)
- Student enrollment & progress tracking
- Dashboard for **Admin & Students**
- Database-driven content management
- Responsive and clean UI

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Server:** XAMPP / Apache

---

## 📥 Installation Guide

### 1. Prerequisites
- [XAMPP](https://www.apachefriends.org/)
- A text editor like **VS Code** / **Sublime** / **Notepad++**

### 2. Steps

1. Move the project folder to your **XAMPP** `htdocs` directory.
2. Start **Apache** and **MySQL** from XAMPP Control Panel.
3. Open [http://localhost/phpmyadmin](http://localhost/phpmyadmin) and create a database:
   ```
   olms
   ```
4. Import the provided **olms.sql** file (found inside the project folder).
5. Open your browser and visit:
   ```
   http://localhost/OLMS
   ```

---

## 🔑 Default Login Credentials

**Admin Login**  
- **Email:** `admin@example.com`  
- **Password:** `admin`

**Student Login**  
- Register as a new student to create your own login credentials.

---

## 📂 Project Structure

```
OLMS/
├── application/
│   ├── controllers/
│   ├── models/
│   ├── views/
├── assets/
├── database/
│   └── olms.sql
├── index.php
└── README.md
```

---

## 🤝 Contributing
1. **Fork** the repository
2. **Create** a new branch
3. **Commit** your changes
4. **Submit** a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.  
See the [LICENSE](./LICENSE) file for details.
