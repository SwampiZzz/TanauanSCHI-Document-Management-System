# TSCHI - Document Management System (DMS)

A web-based platform for securely uploading, reviewing, managing, and retrieving documents for the **Tanauan School of Craftsmanship and Home Industries**.

---

## 📌 Features

### ✅ Core Functionality
- **User Roles**: Admin, Moderator, Regular User
- **Secure Login & Registration**
- **Upload PDFs**: Simple form with validation
- **File Management**: Grid/Table view, filtering, search
- **Review Workflow**: Moderators/Admins approve/reject files with remarks
- **Real-time Feedback**: Status badges and success alerts
- **Audit Logs**: Admin dashboard tracks key actions

### ⚙️ Admin Capabilities
- Manage users (promote, demote, delete)
- Review all uploads
- Access activity logs and file charts
- Modify categories

### 🔐 Security
- Role-based access control
- File access protection (only owners or authorized roles)
- Admin override for file deletions and reviews

----------------------

## 💻 Tech Stack

| Technology | Description                         |
|------------|-------------------------------------|
| PHP        | Backend scripting                   |
| MySQL      | Database                            |
| HTML/CSS   | Frontend structure and styling      |
| Bootstrap  | UI Components and Responsive Design |
| JavaScript | Modal control & interactivity       |

----------------------

## 🚀 Installation & Setup

1. **Clone the repository to you local/cloud server's htdocs folder**:
   ```bash
   git clone https://github.com/SwampiZzz/tschi-dms.git
2. Create a database named tschi_dms
3. Import the provided tschi_dms.sql
4. Configure database settings in config.php:
5. Edit $conn = new mysqli("localhost", "root", "", "tschi_dms"); (if necessary)
6. Ensure folders are writable:
   - uploads/
   - elems/profile-picture/
7. Run locally:
8. Open http://localhost/tschi_dms in your browser.
----------------------
## 👤 Developers

This system is developed by 2nd year BSIT students in ACLC College of Tacloban:
- Cesar Janell Medina
- Edmund Sealtiel De Veyra
- Sheila Mae Comandao
----------------------
📄 License
This project is developed for educational purposes and is not open-source for redistribution without permission.
