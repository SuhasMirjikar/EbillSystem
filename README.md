# ⚡ eBill – Online Electricity Billing System

## 📋 Overview
**eBill** is a web-based electricity billing management system developed using **PHP**, **MySQL**, **HTML**, **CSS**, and **Bootstrap**.  
It simplifies the process of managing electricity bills by allowing users to register, view, and pay their bills online.  
The system also includes an **Admin Dashboard** to manage users, generate bills, and handle customer complaints efficiently.

---

## 🚀 Features

### 👤 User Module
- User signup and secure login  
- View personal bill history and payment details  
- Submit complaints or issues to the admin  
- Simple, responsive dashboard interface  

### 🧑‍💼 Admin Module
- Generate monthly bills for all users  
- Manage user accounts and complaint records  
- Monitor unpaid/defaulter accounts  
- Data visualization and dashboard summaries  

---

## 🛠️ Tech Stack

| Component | Technology |
|------------|-------------|
| Frontend | HTML, CSS, Bootstrap |
| Backend | PHP |
| Database | MySQL |
| Tools Used | XAMPP / WAMP, phpMyAdmin |

---

## 🗂️ Project Structure

```
ebill/
│
├── admin/               # Admin panel PHP files
│   ├── generate_bill.php
│   ├── users.php
│   ├── complaint.php
│   └── ...
│
├── assets/              # CSS, JS, Fonts, and Images
│   ├── css/
│   ├── img/
│   ├── js/
│   └── fonts/
│
├── index.php            # Homepage
├── login.php            # Login page
├── signup.php           # User registration
├── footer.php           # Common footer
└── erdiagram.jpg        # Database ER diagram
```

---

## ⚙️ Installation & Setup

1. **Download or Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/ebill.git
   ```

2. **Move the Folder to Your Server Directory**
   - For **XAMPP**, place it inside:  
     `C:\xampp\htdocs\`
   - For **WAMP**, place it inside:  
     `C:\wamp\www\`

3. **Create the Database**
   - Open **phpMyAdmin**
   - Create a new database named `ebill`
   - Import the SQL file (if provided, e.g., `ebill.sql`)

4. **Run the Application**
   - Open your browser and go to:  
     `http://localhost/ebill/`

---

## 🔐 Login Credentials (Demo)

| Role | Username | Password |
|------|-----------|-----------|
| Admin | admin | admin123 |
| User | user@example.com | user123 |

*(You can modify credentials from the database.)*

---

## 📊 ER Diagram
Included in the project folder as **`erdiagram.jpg`**, depicting the database structure and relationships.

---

## 💡 Future Enhancements
- Integration with online payment gateways  
- Automated email bill notifications  
- Mobile app version using React Native  
- Advanced analytics for admin dashboard  

---

## 🤝 Contributing
Contributions are always welcome!  
If you’d like to improve the system or add features:
1. Fork the repository  
2. Create a new branch  
3. Make your changes  
4. Submit a pull request  

---

## 📜 License
This project is open-source and available under the **MIT License**.

---

## 👨‍💻 Author
**Suhas S Mirjikar**  
🎓 Computer Science Engineering Student, PES University  
🔗 [GitHub](https://github.com/SuhasMirjikar) | [LinkedIn](https://www.linkedin.com/in/suhas-mirjikar-242996250/)
