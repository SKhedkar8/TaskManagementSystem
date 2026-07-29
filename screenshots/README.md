# 📋 Task Management System

A modern **Task Management System** developed using the **Mendix Low-Code Platform**.

This application enables an **Administrator** to manage users, **Managers** to assign and review tasks, and **Employees** to update task progress and receive feedback through a secure role-based workflow.

---

# ✨ Features

## 👨‍💼 Administrator

- Create Manager accounts
- Create Employee accounts
- Manage users
- View reports
- System administration

---

## 👨‍💻 Manager

- Assign tasks
- Set deadlines
- Set task priority
- Review employee work
- Approve or reject tasks
- Provide feedback
- View dashboard statistics

---

## 👩‍💼 Employee

- View assigned tasks
- Update task status
- View manager feedback
- Track task deadlines

---

# 🛠 Technology Stack

| Technology | Used |
|------------|------|
| Mendix Studio Pro | ✅ |
| Atlas UI | ✅ |
| Java Actions | ✅ |
| Microflows | ✅ |
| XPath | ✅ |
| Domain Model | ✅ |
| Security | ✅ |
| Git | ✅ |
| GitHub | ✅ |

---

# 🏗 Project Architecture

```text
Administrator
      │
      ▼
Create Users
      │
      ▼
Manager
      │
      ▼
Assign Tasks
      │
      ▼
Employee
      │
      ▼
Update Task Status
      │
      ▼
Manager Review
      │
      ▼
Feedback & Approval
```

---

# 📸 Application Screenshots

## 🔐 Login Page

![Login Page](screenshots/login-page.png)

---

## 🛡 Administrator Dashboard

![Administrator Dashboard](screenshots/admin-dashboard.png)

---

## 👤 Create User

![Create User](screenshots/create-user.png)

---

## 👨‍💼 Manager Dashboard

![Manager Dashboard](screenshots/manager-dashboard.png)

---

## 📝 Assign Task

![Assign Task](screenshots/assign-task.png)

---

## ✅ Task Review

![Task Review](screenshots/task-review.png)

---

## 👨‍💻 Employee Dashboard

![Employee Dashboard](screenshots/employee-dashboard.png)

---

## 📋 My Tasks

![My Tasks](screenshots/my-tasks.png)

---

## 💬 Feedback

![Feedback](screenshots/feedback.png)

---

## 📊 Statistics

![Statistics](screenshots/statistics.png)

---

## 🏛 System Architecture

![Architecture](screenshots/architecture.png)

---

# 📦 Main Modules

- Administration
- Task Management
- Security
- Statistics
- Reports

---

# 🔄 Workflow

1. Administrator creates user accounts.
2. Manager assigns tasks to employees.
3. Employee updates task status.
4. Manager reviews completed tasks.
5. Manager approves or rejects tasks.
6. Employee views manager feedback.

---

# 🔐 Security

The application uses **Role-Based Access Control (RBAC)**.

### User Roles

- Administrator
- Manager
- Employee

Each role has access only to the pages and data permitted by its assigned permissions.

---

# 🚀 Future Improvements

- Email notifications
- File attachments
- Interactive dashboard charts
- Calendar view
- Mobile responsive design
- Task comments
- Dark / Light theme
- Export reports to Excel

---

# 👨‍💻 Author

**Shreyas Khedkar**

GitHub: https://github.com/SKhedkar8

---

# 📄 License

This project was developed for educational, learning, and portfolio purposes.
