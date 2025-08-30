# 🏠 Real Estate Management System  

![Real Estate Management System](https://img.shields.io/badge/Real%20Estate%20Management%20System-Project-blue?style=for-the-badge&logo=homeadvisor)  

---

## 🛠 Tech Stack  
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)  
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)  
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)  

---

## 📌 Features  
✔️ **User Authentication** – Secure login & registration  
✔️ **Property Listings** – Add, update, and view properties  
✔️ **Advanced Search** – Filter properties by location and price  
✔️ **Admin Dashboard** – Manage users and properties  
✔️ **Responsive UI** – Mobile-friendly and clean design  

---

## ⚙️ Installation & Setup  

Follow these steps to set up the project on your local machine:  

### **1. Clone the Repository**  
```bash
git clone https://github.com/your-username/real-estate-management-system.git
```

### **2. Move to the Project Directory**  
```bash
cd real-estate-management-system
```

### **3. Setup XAMPP / WAMP**  
- Install [XAMPP](https://www.apachefriends.org/) or [WAMP](https://www.wampserver.com/).  
- Start **Apache** and **MySQL**.  

### **4. Configure the Project**  
- Move the project folder into:  
  - For XAMPP: `htdocs`  
  - For WAMP: `www`  

### **5. Create Database**  
- Open **phpMyAdmin** (`http://localhost/phpmyadmin`).  
- Create a new database named **`home_db`**.  
- Import the `home_db.sql` file located in the project folder.  

### **6. Update Database Connection**  
- Open `components/connect.php` and update:  
```php
$servername = "localhost";
$username = "root";
$password = "";
$database = "home_db";
```

### **7. Run the Project**  
Open in browser:  
```
http://localhost/real-estate-management-system/project/home.php
```

---

## ✅ Usage Instructions  
- **User Panel:**  
  - Register as a user and log in.  
  - Search for properties or post your own listings.  
- **Admin Panel:**  
  - Navigate to `http://localhost/real-estate-management-system/project/admin/login.php`  
  - Log in with admin credentials to manage properties and users.  
